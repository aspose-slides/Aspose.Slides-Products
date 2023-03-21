---
title: Konwersja prezentacji programu Microsoft PowerPoint do wielu plików przy użyciu C#
url: /pl/net/conversion/
description: Konwertuj slajdy programu Microsoft PowerPoint na różne pliki, w tym PDF, HTML i formaty obrazów na platformach .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwersja prezentacji Microsoft<sup>®</sup> PowerPoint za pomocą C#" h2="Kody źródłowe C# dla różnych przypadków konwersji do konwersji plików na obrazy, PDF, HTML i inne formaty." >}}

{{% blocks/products/pf/feature-page-summary %}}

Deweloperzy mogą łatwo i szybko konwertować prezentacje Microsoft<sup>®</sup> PowerPoint. Uzyskaj wyniki w krótkim czasie, aby zautomatyzować procesy biznesowe. Omawiamy tutaj kilka przypadków, w których można odczytać lub załadować dowolne dane wejściowe [obsługiwane formaty PowerPoint](https://docs.aspose.com/slides/net/supported-file-formats/) oraz zapisać lub zapisać w dowolnym obsługiwanym formacie wyjściowym. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwersja wewnętrzna plików programu Microsoft PowerPoint" %}}
Zawsze, gdy zachodzi potrzeba zautomatyzowania konwersji między formatami Microsoft<sup>®</sup> PowerPoint. **Biblioteka C# PowerPoint** zawiera klasy umożliwiające osiągnięcie tego celu. Załaduj plik za pomocą [klasy prezentacji](https://apireference.aspose.com/net/slides/aspose.slides/presentation), aby załadować lub odczytać żądany format i wywołać [metodę Save](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) tej samej klasy, określając plik wyjściowy i [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).Format wyjściowy. 
{{% blocks/products/pf/feature-page-code h3="Kod konwertera C# do prezentacji programu Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="C# Konwersja PowerPoint do PDF" %}}

Aby dokładnie przekonwertować slajdy PowerPointa na PDF, programiści mogą załadować dokument przy użyciu klasy Presentation i użyć [klasy PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) dla wszystkich określonych i niestandardowych opcje, takie jak poziom kompresji tekstu, jakość JPEG, zachowanie metaplików, konwertowanie ukrytych slajdów, a także wybieranie określonych slajdów i inne. Nawet istnieje możliwość ochrony przekonwertowanego pliku PDF hasłem.
{{% blocks/products/pf/feature-page-code h3="Kod konwertera C# PowerPoint na PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konwersja Microsoft PowerPoint do HTML" %}}
Zawsze, gdy zachodzi potrzeba osadzania prezentacji na stronach internetowych, konieczne jest przekonwertowanie slajdów do formatu HTML. API zapewnia [klasę HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), użyj go po załadowaniu plików do specjalnych ustawień, takich jak ukryte slajdy, ponieważ domyślnie nie będą być uwzględnione podczas procesu konwersji. Przekaż sfinalizowane opcje do metody Zapisz w celu konwersji.
{{% blocks/products/pf/feature-page-code h3="Kod C# do konwersji programu PowerPoint do HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konwertuj slajdy PowerPointa na formaty obrazu" %}}
Konwertowanie formatów Microsoft<sup>®</sup> PowerPoint na obrazy JPEG, PNG, TIFF itp. to kolejny wspólny przypadek użycia najczęściej używany do tworzenia miniatur slajdów. Proces kodowania jest prosty. Po załadowaniu dokumentu użyj [interfejsu ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide), aby przejść przez każdy slajd. Podczas każdej iteracji użyj (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] wraz z jego mehtodem GetThumbnail mającym dostosowane wymiary obrazu. Na koniec zapisz obraz w wymaganym formacie.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint do kodu konwertera obrazu" %}}
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