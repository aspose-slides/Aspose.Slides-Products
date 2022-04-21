---
title: Konverze prezentace Microsoft PowerPoint do více souborů pomocí Javy
url: /cs/java/conversion/
description: Převádějte prezentace Microsoft PowerPoint do různých souborů včetně HTML, PDF a obrazových formátů v aplikacích založených na Javě.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konverze prezentací Microsoft<sup>®</sup> PowerPoint přes Java" h2="Zdrojové kódy Java pro různé scénáře konverze pro převod snímků do obrázků, HTML, PDF a dalších formátů." >}}

{{% blocks/products/pf/feature-page-summary %}}

Knihovna Java PowerPoint učinila převod prezentací Microsoft<sup>®</sup> PowerPoint Presentation jednoduchou a snadno automatizovatelnou. Vývojáři si mohou vybrat relevantní scénář a integrovat kód pro vylepšení funkčnosti aplikace. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Mezikonverze souborů Microsoft PowerPoint" %}}
Interkonverze souborů Microsoft<sup>®</sup> PowerPoint programově je pouze dvouřádkový kód. Načtěte soubor pomocí [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) a zavolejte metodu uložení s výstupním souborem a [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) jako parametry.

{{% blocks/products/pf/feature-page-code h3="Konverzní kód Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Převod PowerPoint do PDF" %}}

Převod PowerPoint do PDF je běžným případem kvůli obrovskému sdílení souborů PDF. Namísto ručních převodů to programátoři mohou automatizovat a ušetřit čas na spoustu powerpointových prezentací do PDF. Prezentační knihovna poskytuje [třídu PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) pro přizpůsobení konkrétních nastavení, jako je nastavení úrovně komprese textu, úroveň souladu s PDF, kvalita JPEG, definování chování metasouborů, převod skrytých snímků, výběr vybraných snímků a generování zamčených souborů PDF chráněných heslem.

{{% blocks/products/pf/feature-page-code h3="Převodní kód Java PowerPoint do PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Převod Microsoft PowerPoint do HTML" %}}

Vzhledem k tomu, že snímky aplikace PowerPoint nejsou přímo zobrazeny na webových stránkách, je třeba provést konverzi. Programátoři mohou načíst soubor pomocí třídy Presentation, využít [třídu HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) pro konkrétní nastavení HTML a vyvolat metodu uložení.

{{% blocks/products/pf/feature-page-code h3="Java kód pro převod PowerPoint do HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Převod Microsoft PowerPoint na obrázky" %}}
Konverze formátů Microsoft<sup>®</sup> PowerPoint na obrázky JPG, TIFF, PNG atd. je obvykle vhodná pro vytváření miniatur snímků a v mnoha dalších případech. Proces kódování je jednoduchý. Po načtení dokumentu procházejte každý snímek přes [rozhraní ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) a získejte miniaturu ISlide ISlide.getThumbnail(1f, 1f) do [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) a poté uložte do požadovaného formátu obrázku. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint to Image Converter Code" %}}
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