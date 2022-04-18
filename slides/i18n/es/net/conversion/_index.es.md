---
title: Conversión de presentaciones de Microsoft PowerPoint a múltiples archivos usando C#
url: /es/net/conversion/
description: Convierta diapositivas de Microsoft PowerPoint a diferentes archivos, incluidos PDF, HTML y formatos de imagen en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de presentación de Microsoft<sup>®</sup> PowerPoint a través de C#" h2="Códigos fuente de C# para diferentes casos de conversión para convertir archivos a imágenes, PDF, HTML y otros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

Es fácil para los desarrolladores convertir presentaciones de Microsoft<sup>®</sup> PowerPoint con velocidad y precisión. Obtenga los resultados en poco tiempo para automatizar los procesos comerciales. Estamos discutiendo aquí algunos casos para leer o cargar cualquier entrada [formatos de PowerPoint compatibles] (https://docs.aspose.com/slides/net/supported-file-formats/) y escribir o guardar en cualquier formato de salida compatible. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter conversión de archivos de Microsoft PowerPoint" %}}
Siempre que exista la necesidad de automatizar la interconversión de los formatos de Microsoft<sup>®</sup> PowerPoint. **Biblioteca de C# PowerPoint** proporciona clases para lograr este objetivo. Cargue el archivo usando [Clase de presentación](https://apireference.aspose.com/net/slides/aspose.slides/presentation) para cargar o leer el formato deseado y llamando al [Método Guardar](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) de la misma clase especificando el archivo de salida y [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /guardar formato).Formato de salida. 
{{% blocks/products/pf/feature-page-code h3="Código convertidor de C# para presentaciones de Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversión de C# PowerPoint a PDF" %}}

Para convertir diapositivas de PowerPoint a PDF con precisión, los programadores pueden cargar el documento usando la clase Presentation y usar [clase PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) para todas las opciones específicas y personalizadas. opciones como el nivel de compresión del texto, la calidad de Jpeg, el comportamiento de los metarchivos, la conversión de diapositivas ocultas, así como la selección de diapositivas específicas y más. Incluso hay una opción para proteger el archivo PDF convertido con contraseña.
{{% blocks/products/pf/feature-page-code h3="C# Código de conversión de PowerPoint a PDF" %}}

```cs
// Load PowerPoint file
Presentation pptxtopdf = new Presentation("sourceFile.pptx");

// Create PdfOptions class object for specific settings
PdfOptions pptPDFOptions = new PdfOptions();

// Set Jpeg quality
pptPDFOptions.JpegQuality = 90;

// Set behavior for metafiles
pptPDFOptions.SaveMetafilesAsPng = true;

// Set text compression level
pptPDFOptions.TextCompression = PdfTextCompression.Flate;

// Define the PDF 15 standard
pptPDFOptions.Compliance = PdfCompliance.Pdf15;

// Include hidden slides
pptPDFOptions.ShowHiddenSlides = true;

// Setting PDF password and access permissions
pptPDFOptions.Password = "password";
pptPDFOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;

// Save the presentation as PDF
pptxtopdf.Save("csharp-PowerPoint-to.pdf", SaveFormat.Pdf, pptPDFOptions);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversión de Microsoft PowerPoint a HTML" %}}
Siempre que sea necesario incrustar presentaciones en páginas web, será necesario convertir las diapositivas a HTML. La API proporciona [clase HtmlOptions] (https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), utilícela después de cargar los archivos para configuraciones especiales como diapositivas ocultas, ya que de forma predeterminada, estas no incluirse durante el proceso de conversión. Pase las opciones finalizadas al método Guardar para la conversión.
{{% blocks/products/pf/feature-page-code h3="Código C# para la conversión de PowerPoint a HTML" %}}

```cs

// Load source presentation 
Presentation powerpoiontohtml = new Presentation("sourceFile.pptx");

// Create HTML options
HtmlOptions PowerPointhtmlOpt = new HtmlOptions();

// Show hidden slides
PowerPointhtmlOpt.ShowHiddenSlides = true;

// Save the PPTX as HTML
powerpoiontohtml.Save("presentation-to.html", SaveFormat.Html, PowerPointhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir diapositivas de PowerPoint a formatos de imagen" %}}
La conversión de formatos de Microsoft<sup>®</sup> PowerPoint a imágenes JPEG, PNG, TIFF, etc. es otro caso de uso común que se usa principalmente para crear miniaturas de diapositivas. El proceso de codificación es simple. Después de cargar el documento, utilice la [interfaz ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide) para recorrer cada diapositiva. Durante cada iteración, use (Objeto de mapa de bits) [https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] junto con su método GetThumbnail con dimensiones de imagen personalizadas. Finalmente guarde la imagen en el formato requerido.
{{% blocks/products/pf/feature-page-code h3="Código de conversión de PowerPoint a imagen de C#" %}}
```cs
using (Presentation powerpointtoimage = new Presentation("source-file.ppt")){
foreach (ISlide sld in powerpointtoimage.Slides){

// Create a full scale image
Bitmap bmp = sld.GetThumbnail(1f, 1f);
// or use some customized dimensions as sld.GetThumbnail(x, y)

// Save the image
bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
}
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}