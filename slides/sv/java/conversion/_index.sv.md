---
title: Microsoft PowerPoint-presentationskonvertering till flera filer med Java
url: /sv/java/conversion/
description: Konvertera Microsoft PowerPoint Slides till olika filer inklusive HTML, PDF och bildformat i Java-baserade applikationer.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-presentationskonvertering via Java" h2="Java-källkoder för olika konverteringsscenarier för att konvertera bilder till bilder, HTML, PDF och andra format." >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint-biblioteket har gjort konverteringen av Microsoft<sup>®</sup> PowerPoint-presentationer enkel och lätt att automatisera processer. Utvecklare kan välja det relevanta scenariot och integrera koden för att förbättra applikationens funktionalitet. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Interkonvertering av Microsoft PowerPoint-filer" %}}
Interkonvertering av Microsoft<sup>®</sup> PowerPoint-filer programmatiskt är bara en kod på två rader. Ladda filen med [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) och anropa sparametoden som har utdatafilen och [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) som parametrar.

{{% blocks/products/pf/feature-page-code h3="Java-konverteringskod" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint till PDF-konvertering" %}}

PowerPoint till PDF-konvertering är ett vanligt fall på grund av den enorma delningen av PDF-filer. Istället för manuella konverteringar kan programmerare automatisera det och spara tid för en massa PowerPoint-presentationer till PDF. Presentationsbiblioteket tillhandahåller [PdfOptions class](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) för att anpassa specifika inställningar som att ställa in textkomprimeringsnivå, PDF-kompatibilitetsnivå, JPEG-kvalitet, definiera beteendet av metafiler, konvertera dolda bilder, välja utvalda bilder och generera låsta lösenordsskyddade PDF-filer.

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint till PDF-konverteringskod" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint till HTML-konvertering" %}}

Eftersom PowerPoint-bilder inte visas direkt på webbsidor så finns det behov av konvertering. Programmerare kan ladda filen med presentationsklassen, använda [HtmlOptions class](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) för specifika HTML-inställningar och anropa sparmetoden.

{{% blocks/products/pf/feature-page-code h3="Java-kod för PowerPoint till HTML-konvertering" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konvertering av Microsoft PowerPoint till bilder" %}}
Microsoft<sup>®</sup> PowerPoint-format till bilder JPG, TIFF, PNG, etc konvertering är normalt för att skapa miniatyrbilder av diabilder såväl som mycket fler fall. Kodningsprocessen är enkel. Iterera genom varje bild via [ISlide-gränssnitt](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) efter att ha laddat dokumentet, hämta ISlide-miniatyrbilden ISlide.getThumbnail(1f, 1f) i [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) och spara sedan i önskat bildformat. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint till bildkonverteringskod" %}}
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