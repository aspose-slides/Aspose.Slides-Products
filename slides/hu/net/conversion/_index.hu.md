---
title: Microsoft PowerPoint prezentáció konvertálása több fájlba C# használatával
url: /hu/net/conversion/
description: Konvertálja a Microsoft PowerPoint diákat különböző fájlokká, például PDF-, HTML- és képformátumokká .NET-keretrendszeren, .NET Core-on, Windows Azure-on, Mono- vagy Xamarin-platformokon.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint prezentáció konvertálása C#-on keresztül" h2="C# forráskódok különböző konverziós esetekhez a fájlok képekké, PDF-be, HTML-be és más formátumokká konvertálásához." >}}

{{% blocks/products/pf/feature-page-summary %}}

A fejlesztők könnyen konvertálhatják a Microsoft<sup>®</sup> PowerPoint-bemutatókat gyorsan és pontosan. Gyorsan elérheti az eredményeket az üzleti folyamatok automatizálásával. Itt néhány olyan esetet tárgyalunk, amikor be kell olvasni vagy betölteni a [támogatott PowerPoint-formátumokat](https://docs.aspose.com/slides/net/supported-file-formats/), és bármilyen támogatott kimeneti formátumba írni vagy menteni. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint fájlok interkonverziója" %}}
Amikor szükség van a Microsoft<sup>®</sup> PowerPoint formátumok interkonverziójának automatizálására. A **C# PowerPoint könyvtár** osztályokat biztosít a cél eléréséhez. Töltse be a fájlt a [Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation) segítségével a kívánt formátum betöltéséhez vagy olvasásához, és hívja meg a [Mentés módszert](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) a kimeneti fájl és a [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export) megadásával /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="C# konvertáló kód a Microsoft PowerPoint bemutatókhoz" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint konvertálás PDF-be" %}}

A PowerPoint diák PDF formátumba való pontos konvertálásához a programozók betölthetik a dokumentumot a Presentation osztály használatával, és használhatják a [PdfOptions osztályt](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) minden speciális és egyéni célra. olyan lehetőségek, mint a szövegtömörítési szint, a Jpeg minőség, a metafájlok viselkedése, a rejtett diák konvertálása, valamint az adott diák kiválasztása stb. Még arra is van lehetőség, hogy a konvertált PDF fájlt jelszóval védje.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint PDF konvertáló kód" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konverzió Microsoft PowerPointból HTML-be" %}}
Amikor valamikor prezentációkat kell beágyazni a weboldalakba, akkor a diákat HTML formátumba kell konvertálni. Az API [HtmlOptions osztályt](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions) biztosít. Használja a fájlok betöltése után speciális beállításokhoz, például rejtett diákhoz, mivel ezek alapértelmezés szerint nem fognak be kell venni az átalakítási folyamat során. Adja át a véglegesített beállításokat a Konverziós mód mentése menüpontnak.
{{% blocks/products/pf/feature-page-code h3="C# kód a PowerPoint HTML konvertálásához" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PowerPoint diákat képformátumokká" %}}
A Microsoft<sup>®</sup> PowerPoint formátumok JPEG, PNG, TIFF stb. formátumú képekké konvertálása egy másik elterjedt eset, amelyet többnyire diabélyegképek létrehozására használnak. A kódolási folyamat egyszerű. A dokumentum betöltése után az [ISlide felület](https://apireference.aspose.com/net/slides/aspose.slides/islide) segítségével ismételje meg az egyes diákat. Minden iteráció során használja (Bitmap Object) [https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] a GetThumbnail metódusával együtt, amely testreszabott képméretekkel rendelkezik. Végül mentse a képet a kívánt formátumban.
{{% blocks/products/pf/feature-page-code h3="A C# PowerPoint képátalakító kódja" %}}
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