---
title: Conversie van Microsoft PowerPoint-presentatie naar meerdere bestanden met Java
url: /nl/java/conversion/
description: Converteer Microsoft PowerPoint-dia's naar verschillende bestanden, waaronder HTML, PDF en afbeeldingsindelingen binnen op Java gebaseerde toepassingen.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-presentatieconversie via Java" h2="Java-broncodes voor verschillende conversiescenario's om dia's om te zetten naar afbeeldingen, HTML, PDF en andere formaten." >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint-bibliotheek heeft de conversie van Microsoft<sup>®</sup> PowerPoint-presentaties eenvoudig en gemakkelijk te automatiseren processen gemaakt. Ontwikkelaars kunnen het relevante scenario selecteren en de code integreren om de functionaliteit van de applicatie te verbeteren. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Interconversie van Microsoft PowerPoint-bestanden" %}}
Interconversie van Microsoft<sup>®</sup> PowerPoint-bestanden is programmatisch slechts een code van twee regels. Laad het bestand met behulp van [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) en roep de opslagmethode aan met het uitvoerbestand en [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) als parameters.

{{% blocks/products/pf/feature-page-code h3="Java-conversiecode" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint naar PDF-conversie" %}}

PowerPoint naar PDF-conversie is een veelvoorkomend geval vanwege het enorme delen van PDF-bestanden. In plaats van handmatige conversies, kunnen programmeurs het automatiseren en tijd besparen voor een heleboel PowerPoint-presentaties naar PDF. Presentatiebibliotheek biedt [PdfOptions class](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) voor het aanpassen van specifieke instellingen, zoals het instellen van tekstcompressieniveau, PDF-complianceniveau, JPEG-kwaliteit, het gedrag definiëren van metabestanden, het converteren van verborgen dia's, het kiezen van geselecteerde dia's en het genereren van vergrendelde, met een wachtwoord beveiligde PDF-bestanden.

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint naar PDF-conversiecode" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint naar HTML-conversie" %}}

Aangezien PowerPoint-dia's niet direct op webpagina's worden weergegeven, is conversie nodig. Programmeurs kunnen bestanden laden met de klasse Presentation, [HtmlOptions class](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) gebruiken voor specifieke HTML-instellingen en de opslagmethode aanroepen.

{{% blocks/products/pf/feature-page-code h3="Java-code voor conversie van PowerPoint naar HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Conversie van Microsoft PowerPoint naar afbeeldingen" %}}
Microsoft<sup>®</sup> PowerPoint-indelingen naar afbeeldingen De conversie van JPG, TIFF, PNG, enz. is normaal gesproken bedoeld voor het maken van miniaturen van dia's en nog veel meer gevallen. Het coderingsproces is eenvoudig. Doorloop elke dia via [ISlide-interface](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) na het laden van het document, haal de ISlide-miniatuur ISlide.getThumbnail (1f, 1f) in [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) en sla het vervolgens op in het vereiste afbeeldingsformaat. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint naar Image Converter-code" %}}
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