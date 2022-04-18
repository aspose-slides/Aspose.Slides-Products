---
title: Conversión de presentaciones de Microsoft PowerPoint a múltiples archivos usando Java
url: /es/java/conversion/
description: Convierta diapositivas de Microsoft PowerPoint a diferentes archivos, incluidos HTML, PDF y formatos de imagen dentro de aplicaciones basadas en Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de presentaciones de Microsoft<sup>®</sup> PowerPoint a través de Java" h2="Códigos fuente de Java para varios escenarios de conversión para convertir diapositivas en imágenes, HTML, PDF y otros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

La biblioteca Java PowerPoint ha hecho que la conversión de presentaciones de Microsoft<sup>®</sup> PowerPoint sea simple y fácil de automatizar procesos. Los desarrolladores pueden seleccionar el escenario relevante e integrar el código para mejorar la funcionalidad de la aplicación. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter conversión de archivos de Microsoft PowerPoint" %}}
La interconversión de archivos de Microsoft<sup>®</sup> PowerPoint mediante programación es solo un código de dos líneas. Cargue el archivo usando [Clase de presentación](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) y llame al método de guardar que tiene el archivo de salida y [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) como parámetros.

{{% blocks/products/pf/feature-page-code h3="Código de conversión de Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversión de PowerPoint a PDF" %}}

La conversión de PowerPoint a PDF es un caso común debido al enorme intercambio de archivos PDF. En lugar de conversiones manuales, los programadores pueden automatizarlas y ahorrar tiempo para un montón de presentaciones de PowerPoint a PDF. La biblioteca de presentaciones proporciona [clase PdfOptions] (https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) para personalizar configuraciones específicas como establecer el nivel de compresión de texto, el nivel de cumplimiento de PDF, la calidad JPEG, definir el comportamiento de metarchivos, convertir diapositivas ocultas, elegir diapositivas seleccionadas y generar archivos PDF bloqueados y protegidos con contraseña.

{{% blocks/products/pf/feature-page-code h3="Código de conversión de Java PowerPoint a PDF" %}}

```cs
// Load file
Presentation powerpointopdf = new Presentation("srcFile.pptx");

// Create PdfOptions class object
PdfOptions slidetopdfOpt = new PdfOptions();
               
// Set JPEG Quality
slidetopdfOpt.setJpegQuality((byte) 90);

// Define behavior for Metafiles
slidetopdfOpt.setSaveMetafilesAsPng(true);

// Set Text Compression level
slidetopdfOpt.setTextCompression(PdfTextCompression.Flate);

// Define the PDF standard
slidetopdfOpt.setCompliance(PdfCompliance.Pdf15);
              
INotesCommentsLayoutingOptions options = slidetopdfOpt.getNotesCommentsLayouting();
options.setNotesPosition(NotesPositions.BottomFull);

// Specify that the generated document should include hidden slides
slidetopdfOpt.setShowHiddenSlides(true);
	
// Setting PDF password
slidetopdfOpt.setPassword("password");	

// Save the presentation to PDF with specified options
powerpointopdf.save("java-powerpoint-to.pdf", SaveFormat.Pdf, slidetopdfOpt);


// Setting array of slides positions
// int[] slides = new int[] { 2, 3, 5 };

// Save the presentation to PDF
// powerpointopdf.save("java-powerpoint-to.pdf", slides, SaveFormat.Pdf);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversión de Microsoft PowerPoint a HTML" %}}

Como las diapositivas de PowerPoint no se muestran directamente en las páginas web, es necesario convertirlas. Los programadores pueden cargar archivos usando la clase Presentation, utilizar [clase HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) para configuraciones HTML específicas e invocar el método de guardado.

{{% blocks/products/pf/feature-page-code h3="Código Java para la conversión de PowerPoint a HTML" %}}

```cs

// Load the file
Presentation powerpointohtml = new Presentation("srcFile.pptx");

// Create HTML options
HtmlOptions pptxhtmlOpt = new HtmlOptions();

// Displaying hidden slides
pptxhtmlOpt.setShowHiddenSlides(true);

// Save the PPTX as HTML
powerpointohtml.save("java-powerpoint-to.html", SaveFormat.Html, pptxhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversión de Microsoft PowerPoint a Imágenes" %}}
La conversión de formatos de Microsoft<sup>®</sup> PowerPoint a imágenes JPG, TIFF, PNG, etc. es normalmente para crear miniaturas de diapositivas y muchos más casos. El proceso de codificación es simple. Repita cada diapositiva a través de [ISlide interface](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) después de cargar el documento, obtenga la miniatura de ISlide ISlide.getThumbnail(1f, 1f) en [Objeto BufferedImage](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) y luego guárdelo en el formato de imagen requerido. 

{{% blocks/products/pf/feature-page-code h3="Código de conversión de PowerPoint a imagen de Java" %}}
```cs
// Load the PowerPoint document
Presentation PowerPointtoImage = new Presentation("templatefile.pptx");


// for generating a full scale image
// BufferedImage bi = sld.getThumbnail(1f, 1f);

// for Customized dimensions, define dimensions
int finalX = 1200;
int finalY = 800;

// Get scaled values of X and Y
float DimensionX = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getWidth()) * finalX;
float DimensionY = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getHeight()) * finalY;

// Loop through each slide in the presentation
for (ISlide sld : PowerPointtoImage.getSlides()) {
	
// Create a full scale image
BufferedImage bi = sld.getThumbnail(DimensionX, DimensionY);

// Create a new file
File outputfile = new File(sld.getSlideNumber() + "_Slide.jpg");
	
// Save the image to disk in JPEG format
ImageIO.write(bi, "jpg", outputfile);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}