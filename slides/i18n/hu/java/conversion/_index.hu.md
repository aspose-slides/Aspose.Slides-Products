---
title: Microsoft PowerPoint prezentáció konvertálása több fájlba Java használatával
url: /hu/java/conversion/
description: Konvertálja a Microsoft PowerPoint diákat különböző fájlokká, beleértve a HTML, PDF és képformátumokat a Java alapú alkalmazásokban.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-bemutatókonverzió Java-n keresztül" h2="Java-forráskódok különféle konverziós forgatókönyvekhez a diák képek, HTML, PDF és egyéb formátumokká konvertálásához." >}}

{{% blocks/products/pf/feature-page-summary %}}

A Java PowerPoint könyvtár egyszerűvé és könnyen automatizálhatóvá tette a Microsoft<sup>®</sup> PowerPoint Presentations konvertálását. A fejlesztők kiválaszthatják a megfelelő forgatókönyvet, és integrálhatják a kódot az alkalmazás funkcionalitásának javítása érdekében. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint fájlok interkonverziója" %}}
A Microsoft<sup>®</sup> PowerPoint-fájlok programozott interkonvertálása mindössze egy kétsoros kód. Töltse be a fájlt a [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) segítségével, és hívja meg a kimeneti fájlt és a [SaveFormat](https://apireference) mentési módszert .aspose.com/slides/java/com.aspose.slides/SaveFormat) paraméterként.

{{% blocks/products/pf/feature-page-code h3="Java konverziós kód" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint konvertálása PDF-be" %}}

A PowerPoint PDF-be konvertálása gyakori eset a PDF-fájlok hatalmas megosztása miatt. A kézi átalakítások helyett a programozók automatizálhatják, és időt takaríthatnak meg a PowerPoint-prezentációk PDF formátumba történő elkészítéséhez. A prezentációs könyvtár [PdfOptions osztályt](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) biztosít az olyan speciális beállítások testreszabásához, mint a szövegtömörítési szint, a PDF megfelelőségi szint, a JPEG minőség beállítása, a viselkedés meghatározása metafájlok, rejtett diák konvertálása, kiválasztott diák kiválasztása és zárolt, jelszóval védett PDF fájlok generálása.

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint PDF konvertáló kód" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konverzió Microsoft PowerPointból HTML-be" %}}

Mivel a PowerPoint diák nem jelenik meg közvetlenül a weboldalakon, ezért átalakításra van szükség. A programozók a Presentation osztály használatával tölthetnek be fájlt, használhatják a [HtmlOptions osztályt](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) bizonyos HTML-beállításokhoz, és meghívhatják a mentési módszert.

{{% blocks/products/pf/feature-page-code h3="Java kód a PowerPoint HTML konvertálásához" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint konvertálása képekké" %}}
A Microsoft<sup>®</sup> PowerPoint formátumok JPG, TIFF, PNG stb. formátumú képekké való konvertálása általában diabélyegképek, valamint sok más eset létrehozására szolgál. A kódolási folyamat egyszerű. A dokumentum betöltése után ismételje meg az egyes diákat az [ISlide felületén](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide), és töltse be az ISlide bélyegképét az ISlide.getThumbnail(1f, 1f) [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html), majd mentse a kívánt képformátumba. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint képátalakító kód" %}}
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