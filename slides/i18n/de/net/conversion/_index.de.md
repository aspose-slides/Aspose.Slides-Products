---
title: Konvertierung von Microsoft PowerPoint-Präsentationen in mehrere Dateien mit C#
url: /de/net/conversion/
description: Konvertieren Sie Microsoft PowerPoint-Folien in verschiedene Dateien, einschließlich PDF-, HTML- und Bildformate auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertierung von Microsoft<sup>®</sup> PowerPoint-Präsentationen über C#" h2="C#-Quellcodes für verschiedene Konvertierungsfälle zum Konvertieren von Dateien in Bilder, PDF, HTML und andere Formate." >}}

{{% blocks/products/pf/feature-page-summary %}}

Für die Entwickler ist es einfach, Microsoft<sup>®</sup> PowerPoint-Präsentationen schnell und genau zu konvertieren. Erhalten Sie innerhalb kürzester Zeit die Ergebnisse für die Automatisierung der Geschäftsprozesse. Wir diskutieren hier einige Fälle zum Lesen oder Laden von Eingaben [unterstützte PowerPoint-Formate](https://docs.aspose.com/slides/net/supported-file-formats/) und zum Schreiben oder Speichern in einem beliebigen unterstützten Ausgabeformat. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Zwischenkonvertierung von Microsoft PowerPoint-Dateien" %}}
Wann immer es notwendig ist, die Interkonvertierung von Microsoft<sup>®</sup> PowerPoint-Formaten zu automatisieren. Die **C#-PowerPoint-Bibliothek** stellt Klassen bereit, um dieses Ziel zu erreichen. Laden Sie die Datei mit [Präsentationsklasse](https://apireference.aspose.com/net/slides/aspose.slides/presentation), um das gewünschte Format zu laden oder zu lesen, und rufen Sie die [Save-Methode](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) derselben Klasse durch Angabe der Ausgabedatei und [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).Ausgabeformat. 
{{% blocks/products/pf/feature-page-code h3="C#-Konvertercode für Microsoft PowerPoint-Präsentationen" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="C#-PowerPoint-zu-PDF-Konvertierung" %}}

Zum genauen Konvertieren von PowerPoint-Folien in PDF können Programmierer das Dokument mithilfe der Presentation-Klasse laden und [PdfOptions-Klasse](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) für alle spezifischen und benutzerdefinierten Optionen verwenden Optionen wie Textkomprimierungsgrad, Jpeg-Qualität, das Verhalten von Metadateien, Konvertieren versteckter Folien sowie Auswählen bestimmter Folien und mehr. Es besteht sogar die Möglichkeit, die konvertierte PDF-Datei mit einem Passwort zu schützen.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint-zu-PDF-Konvertercode" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konvertierung von Microsoft PowerPoint in HTML" %}}
Wann immer Präsentationen in Webseiten eingebettet werden müssen, müssen Folien in HTML konvertiert werden. Die API bietet [HtmlOptions-Klasse](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions). Verwenden Sie sie nach dem Laden der Dateien für spezielle Einstellungen wie ausgeblendete Folien, da dies standardmäßig nicht der Fall ist während des Konvertierungsprozesses enthalten sein. Übergeben Sie die endgültigen Optionen an Methode zur Konvertierung speichern.
{{% blocks/products/pf/feature-page-code h3="C#-Code für PowerPoint-zu-HTML-Konvertierung" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PowerPoint-Folien in Bildformate" %}}
Das Konvertieren von Microsoft<sup>®</sup> PowerPoint-Formaten in JPEG-, PNG-, TIFF-Bilder usw. ist ein weiterer häufiger Anwendungsfall, der hauptsächlich zum Erstellen von Miniaturansichten von Folien verwendet wird. Der Codierungsprozess ist einfach. Verwenden Sie nach dem Laden des Dokuments [ISlide-Schnittstelle](https://apireference.aspose.com/net/slides/aspose.slides/islide), um jede Folie zu durchlaufen. Verwenden Sie während jeder Iteration (Bitmap-Objekt)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] zusammen mit seinem GetThumbnail-Verfahren mit benutzerdefinierten Bildabmessungen. Speichern Sie abschließend das Bild im gewünschten Format.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint-zu-Bild-Konverter-Code" %}}
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