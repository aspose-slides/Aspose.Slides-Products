---
title: Conversão de apresentação do Microsoft PowerPoint para vários arquivos usando Java
url: /pt/java/conversion/
description: Converta slides do Microsoft PowerPoint para diferentes arquivos, incluindo HTML, PDF e formatos de imagem em aplicativos baseados em Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversão de apresentação do Microsoft<sup>®</sup> PowerPoint via Java" h2="Códigos-fonte Java para vários cenários de conversão para converter slides em imagens, HTML, PDF e outros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

A biblioteca Java PowerPoint tornou a conversão do Microsoft<sup>®</sup> PowerPoint Presentations simples e fácil de automatizar processos. Os desenvolvedores podem selecionar o cenário relevante e integrar o código para aprimorar a funcionalidade do aplicativo. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Interconversão de arquivos do Microsoft PowerPoint" %}}
A interconversão de arquivos do Microsoft<sup>®</sup> PowerPoint programaticamente é apenas um código de duas linhas. Carregue o arquivo usando [Classe de apresentação](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) e chame o método save com o arquivo de saída e [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) como parâmetros.

{{% blocks/products/pf/feature-page-code h3="Código de conversão Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversão de PowerPoint para PDF" %}}

A conversão de PowerPoint para PDF é um caso comum devido ao grande compartilhamento de arquivos PDF. Em vez de conversões manuais, os programadores podem automatizar e economizar tempo para várias apresentações do PowerPoint para PDF. A biblioteca de apresentações fornece [classe PDFOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) para personalizar configurações específicas, como definir o nível de compactação de texto, nível de conformidade do PDF, qualidade JPEG, definir o comportamento de meta-arquivos, convertendo slides ocultos, escolhendo slides selecionados e gerando arquivos PDF protegidos por senha bloqueados.

{{% blocks/products/pf/feature-page-code h3="Código de conversão Java PowerPoint para PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Conversão do Microsoft PowerPoint para HTML" %}}

Como os slides do PowerPoint não são exibidos diretamente nas páginas da Web, há necessidade de conversão. Os programadores podem carregar o arquivo usando a classe Presentation, utilizar a [classe HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) para configurações HTML específicas e invocar o método save.

{{% blocks/products/pf/feature-page-code h3="Código Java para conversão de PowerPoint para HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Conversão de imagens do Microsoft PowerPoint para imagens" %}}
Formatos do Microsoft<sup>®</sup> PowerPoint para imagens JPG, TIFF, PNG, etc. A conversão é normalmente para criar miniaturas de slides, bem como muitos outros casos. O processo de codificação é simples. Faça a iteração em cada slide por meio da [interface ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) depois de carregar o documento, obtenha a miniatura ISlide ISlide.getThumbnail(1f, 1f) em [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) e salve no formato de imagem necessário. 

{{% blocks/products/pf/feature-page-code h3="Código Java PowerPoint para Conversor de Imagem" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}