---
title: Microsoft PowerPoint-presentationskonvertering till flera filer med C#
url: /sv/net/conversion/
description: Konvertera Microsoft PowerPoint Slides till olika filer inklusive PDF, HTML och bildformat på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin Platforms.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-presentationskonvertering via C#" h2="C#-källkoder för olika konverteringsfall för att konvertera filer till bilder, PDF, HTML och andra format." >}}

{{% blocks/products/pf/feature-page-summary %}}

Det är lätt för utvecklarna att konvertera Microsoft<sup>®</sup> PowerPoint-presentationer med snabbhet och noggrannhet. Få resultaten inom nolltid för att automatisera affärsprocesserna. Vi diskuterar här några fall för att läsa eller ladda någon indata [PowerPoint-format som stöds](https://docs.aspose.com/slides/net/supported-file-formats/) och skriva eller spara till valfritt utdataformat som stöds. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Interkonvertering av Microsoft PowerPoint-filer" %}}
Närhelst det finns behov av att automatisera interkonverteringen av Microsoft<sup>®</sup> PowerPoint-format. **C# PowerPoint-biblioteket** tillhandahåller klasser för att uppnå detta mål. Ladda filen med [Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation) för att ladda eller läsa det önskade formatet och anropa [Save method](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) av samma klass genom att ange utdatafilen och [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="C#-konverteringskod för Microsoft PowerPoint-presentationer" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint till PDF-konvertering" %}}

För att konvertera PowerPoint-bilder till PDF korrekt kan programmerare ladda dokumentet med Presentation class och använda [PdfOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) för alla specifika och anpassade alternativ som textkomprimeringsnivå, Jpeg-kvalitet, metafilers beteende, konvertering av dolda bilder samt val av specifika bilder och mer. Även det finns möjlighet att skydda den konverterade PDF-filen med lösenord.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint till PDF-konverteringskod" %}}

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
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf pdf-to-html pdf-to-image pdf-to-jpg pdf-to-png pdf-to-svg pdf-to-tiff pdf-to-xml" >}}


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint till HTML-konvertering" %}}
När det någonsin finns behov av att bädda in presentationer på webbsidor, då finns det ett behov av att konvertera bilder till HTML. API tillhandahåller [HtmlOptions-klass](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), Använd det efter att ha laddat filerna för speciella inställningar som dolda bilder, eftersom dessa som standard inte kommer att inkluderas under konverteringsprocessen. Skicka de slutförda alternativen till Spara-metoden för konvertering.
{{% blocks/products/pf/feature-page-code h3="C#-kod för PowerPoint till HTML-konvertering" %}}

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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html html-to-image html-to-jpg html-to-pdf html-to-tiff html-to-xml" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera PowerPoint-bilder till bildformat" %}}
Att konvertera Microsoft<sup>®</sup> PowerPoint-format till bilder JPEG, PNG, TIFF etc är ett annat vanligt användningsfall som oftast används för att skapa miniatyrbilder av bilder. Kodningsprocessen är enkel. När du har laddat dokumentet använder du [ISlide-gränssnitt](https://apireference.aspose.com/net/slides/aspose.slides/islide) för att iterera genom varje bild. Under varje iteration, använd (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] tillsammans med dess GetThumbnail-mehtod med anpassade bildmått. Spara slutligen bilden i önskat format.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint till bildkonverteringskod" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp image-to-jpg image-to-pdf jpg-to-image jpg-to-pdf jpg-to-png png-to-jpg png-to-pdf png-to-svg svg-to-png" >}}