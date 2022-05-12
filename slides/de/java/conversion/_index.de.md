---
title: Konvertierung von Microsoft PowerPoint-Präsentationen in mehrere Dateien mit Java
url: /de/java/conversion/
description: Konvertieren Sie Microsoft PowerPoint-Folien in verschiedene Dateien, einschließlich HTML-, PDF- und Bildformate in Java-basierten Anwendungen.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertierung von Microsoft<sup>®</sup> PowerPoint-Präsentationen über Java" h2="Java-Quellcodes für verschiedene Konvertierungsszenarien zum Konvertieren von Folien in Bilder, HTML, PDF und andere Formate." >}}

{{% blocks/products/pf/feature-page-summary %}}

Die Java-PowerPoint-Bibliothek hat die Konvertierung von Microsoft<sup>®</sup>-PowerPoint-Präsentationen einfach und leicht zu automatisierende Prozesse gemacht. Entwickler können das relevante Szenario auswählen und den Code integrieren, um die Anwendungsfunktionalität zu erweitern. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Zwischenkonvertierung von Microsoft PowerPoint-Dateien" %}}
Die programmgesteuerte Konvertierung von Microsoft<sup>®</sup> PowerPoint-Dateien ist nur ein zweizeiliger Code. Laden Sie die Datei mit [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) und rufen Sie die save-Methode mit der Ausgabedatei und [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) als Parameter.

{{% blocks/products/pf/feature-page-code h3="Java-Konvertierungscode" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint-zu-PDF-Konvertierung" %}}

Die Konvertierung von PowerPoint in PDF ist ein häufiger Fall, da PDF-Dateien in großem Umfang geteilt werden. Anstelle manueller Konvertierungen können Programmierer sie automatisieren und Zeit für eine Reihe von PowerPoint-Präsentationen in PDF sparen. Die Präsentationsbibliothek bietet [PdfOptions-Klasse](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) zum Anpassen bestimmter Einstellungen wie Festlegen der Textkomprimierungsstufe, PDF-Konformitätsstufe, JPEG-Qualität, Definieren des Verhaltens von Metadateien, Konvertieren versteckter Folien, Auswählen ausgewählter Folien und Generieren von gesperrten passwortgeschützten PDF-Dateien.

{{% blocks/products/pf/feature-page-code h3="Konvertierungscode für Java PowerPoint in PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konvertierung von Microsoft PowerPoint in HTML" %}}

Da PowerPoint-Folien nicht direkt auf Webseiten angezeigt werden, ist eine Konvertierung erforderlich. Programmierer können Dateien mithilfe der Präsentationsklasse laden, [HtmlOptions-Klasse](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) für bestimmte HTML-Einstellungen verwenden und die Speichermethode aufrufen.

{{% blocks/products/pf/feature-page-code h3="Java-Code für PowerPoint-zu-HTML-Konvertierung" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konvertierung von Microsoft PowerPoint in Bilder" %}}
Die Konvertierung von Microsoft<sup>®</sup> PowerPoint-Formaten in Bilder JPG, TIFF, PNG usw. dient normalerweise zum Erstellen von Miniaturansichten von Folien sowie für viele andere Fälle. Der Codierungsprozess ist einfach. Durchlaufen Sie jede Folie über die [ISlide-Schnittstelle](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide), nachdem Sie das Dokument geladen haben, und rufen Sie die ISlide-Miniaturansicht ISlide.getThumbnail(1f, 1f) ab [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) und speichern Sie dann im erforderlichen Bildformat. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint to Image Converter-Code" %}}
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