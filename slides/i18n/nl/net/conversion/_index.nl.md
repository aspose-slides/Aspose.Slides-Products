---
title: Microsoft PowerPoint-presentatieconversie naar meerdere bestanden met C #
url: /nl/net/conversion/
description: Converteer Microsoft PowerPoint-dia's naar verschillende bestanden, waaronder PDF-, HTML- en afbeeldingsformaten op .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-presentatieconversie via C#" h2="C# Broncodes voor verschillende conversiegevallen om bestanden om te zetten naar afbeeldingen, PDF, HTML en andere formaten." >}}

{{% blocks/products/pf/feature-page-summary %}}

Het is gemakkelijk voor de ontwikkelaars om Microsoft<sup>®</sup> PowerPoint-presentaties snel en nauwkeurig om te zetten. Binnen de kortste keren de resultaten voor het automatiseren van de bedrijfsprocessen. We bespreken hier enkele gevallen om invoer [ondersteunde PowerPoint-indelingen](https://docs.aspose.com/slides/net/supported-file-formats/) te lezen of te laden en naar elk ondersteund uitvoerformaat te schrijven of op te slaan. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Interconversie van Microsoft PowerPoint-bestanden" %}}
Wanneer het nodig is om de interconversie van Microsoft<sup>®</sup> PowerPoint-formaten te automatiseren. **C# PowerPoint-bibliotheek** biedt lessen om dit doel te bereiken. Laad het bestand met [Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation) om het gewenste formaat te laden of te lezen en roep de [Save-methode](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) van dezelfde klasse door het uitvoerbestand en [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export) op te geven /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="C#-conversiecode voor Microsoft PowerPoint-presentaties" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint naar PDF-conversie" %}}

Om PowerPoint-dia's nauwkeurig naar PDF te converteren, kunnen programmeurs het document laden met de presentatieklasse en [PdfOptions-klasse](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) gebruiken voor alle specifieke en aangepaste opties zoals tekstcompressieniveau, Jpeg-kwaliteit, het gedrag van metabestanden, het converteren van verborgen dia's en het selecteren van specifieke dia's en meer. Er is zelfs een optie om het geconverteerde PDF-bestand met een wachtwoord te beveiligen.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint naar PDF Converter-code" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint naar HTML-conversie" %}}
Wanneer het ooit nodig is om presentaties in webpagina's in te sluiten, dan is het nodig om dia's naar HTML te converteren. API biedt [HtmlOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), gebruik het na het laden van de bestanden voor speciale instellingen zoals verborgen dia's, zoals standaard niet zullen worden opgenomen tijdens het conversieproces. Geef de definitieve opties door aan de Save-methode voor conversie.
{{% blocks/products/pf/feature-page-code h3="C#-code voor conversie van PowerPoint naar HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PowerPoint-dia's converteren naar afbeeldingsindelingen" %}}
Microsoft<sup>®</sup> PowerPoint-formaten converteren naar afbeeldingen JPEG, PNG, TIFF enz. is een ander veelgebruikt gebruiksvoorbeeld dat meestal wordt gebruikt voor het maken van miniatuurweergaven van dia's. Het coderingsproces is eenvoudig. Gebruik na het laden van het document [ISlide-interface](https://apireference.aspose.com/net/slides/aspose.slides/islide) om door elke dia te bladeren. Gebruik tijdens elke iteratie (Bitmap-object) [https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] samen met de GetThumbnail-methode met aangepaste afbeeldingsdimensies. Sla ten slotte de afbeelding op in het gewenste formaat.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint naar Image Converter-code" %}}
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