---
title: Konverze prezentace Microsoft PowerPoint do více souborů pomocí C#
url: /cs/net/conversion/
description: Převeďte prezentace Microsoft PowerPoint do různých souborů včetně PDF, HTML a obrazových formátů na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konverze prezentace Microsoft<sup>®</sup> PowerPoint přes C#" h2="Zdrojové kódy C# pro různé případy konverze pro převod souborů do obrázků, PDF, HTML a dalších formátů." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře je snadné rychle a přesně převádět prezentace Microsoft<sup>®</sup> PowerPoint. Získejte výsledky během okamžiku pro automatizaci obchodních procesů. Diskutujeme zde o několika případech čtení nebo načítání jakéhokoli vstupu [podporované formáty PowerPoint](https://docs.aspose.com/slides/net/supported-file-formats/) a zápisu nebo uložení do libovolného podporovaného výstupního formátu. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Mezikonverze souborů Microsoft PowerPoint" %}}
Kdykoli je potřeba automatizovat vzájemnou konverzi formátů Microsoft<sup>®</sup> PowerPoint. **Knihovna C# PowerPoint** poskytuje třídy k dosažení tohoto cíle. Načtěte soubor pomocí [Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation), abyste načetli nebo načetli požadovaný formát a zavolejte [Save method](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) stejné třídy zadáním výstupního souboru a [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Kód C# Converter pro prezentace Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Převod C# PowerPointu do PDF" %}}

Pro přesný převod PowerPoint snímků do PDF mohou programátoři načíst dokument pomocí třídy Presentation a použít [třídu PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) pro všechny specifické a vlastní možnosti, jako je úroveň komprese textu, kvalita Jpeg, chování metasouborů, převod skrytých snímků a také výběr konkrétních snímků a další. Dokonce existuje možnost chránit převedený soubor PDF heslem.
{{% blocks/products/pf/feature-page-code h3="Kód C# PowerPoint pro převodník PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Převod Microsoft PowerPoint do HTML" %}}
Kdykoli je potřeba vložit prezentace na webové stránky, pak je potřeba převést snímky do HTML. API poskytuje [třídu HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), použijte jej po načtení souborů pro speciální nastavení, jako jsou skryté snímky, protože ve výchozím nastavení nebudou být zahrnuty během procesu převodu. Předejte finalizované možnosti metodě Uložit pro převod.
{{% blocks/products/pf/feature-page-code h3="C# kód pro převod PowerPoint do HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Převeďte PowerPointové snímky do obrazových formátů" %}}
Převod formátů Microsoft<sup>®</sup> PowerPoint na obrázky JPEG, PNG, TIFF atd. je dalším běžným případem použití, který se většinou používá pro vytváření miniatur snímků. Proces kódování je jednoduchý. Po načtení dokumentu použijte [ISlide interface](https://apireference.aspose.com/net/slides/aspose.slides/islide) k iteraci každého snímku. Během každé iterace použijte (objekt bitmapy)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] spolu s jeho nástrojem GetThumbnail s přizpůsobenými rozměry obrázku. Nakonec uložte obrázek v požadovaném formátu.
{{% blocks/products/pf/feature-page-code h3="Kód C# PowerPoint to Image Converter" %}}
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