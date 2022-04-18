---
title: Konwersja prezentacji programu Microsoft PowerPoint do wielu plików przy użyciu języka Java
url: /pl/java/conversion/
description: Konwertuj slajdy programu Microsoft PowerPoint do różnych plików, w tym HTML, PDF i obrazów w aplikacjach opartych na języku Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwersja prezentacji Microsoft<sup>®</sup> PowerPoint przez Java" h2="Kody źródłowe Java dla różnych scenariuszy konwersji do konwersji slajdów na obrazy, HTML, PDF i inne formaty." >}}

{{% blocks/products/pf/feature-page-summary %}}

Biblioteka Java PowerPoint sprawiła, że ​​konwersja prezentacji Microsoft<sup>®</sup> PowerPoint jest prosta i łatwa do zautomatyzowania. Deweloperzy mogą wybrać odpowiedni scenariusz i zintegrować kod w celu zwiększenia funkcjonalności aplikacji. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwersja wewnętrzna plików programu Microsoft PowerPoint" %}}
Programowa konwersja plików Microsoft<sup>®</sup> PowerPoint to tylko dwa wiersze kodu. Załaduj plik za pomocą [klasy prezentacji](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) i wywołaj metodę save z plikiem wyjściowym i [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) jako parametry.

{{% blocks/products/pf/feature-page-code h3="Kod konwersji Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Konwersja PowerPoint do PDF" %}}

Konwersja PowerPoint do PDF jest częstym przypadkiem ze względu na ogromne udostępnianie plików PDF. Zamiast ręcznych konwersji, programiści mogą to zautomatyzować i zaoszczędzić czas na prezentacje PowerPoint do formatu PDF. Biblioteka prezentacji zapewnia [klasę PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) do dostosowywania określonych ustawień, takich jak ustawianie poziomu kompresji tekstu, poziomu zgodności PDF, jakości JPEG, definiowania zachowania metaplików, konwertowanie ukrytych slajdów, wybieranie wybranych slajdów i generowanie zablokowanych plików PDF chronionych hasłem.

{{% blocks/products/pf/feature-page-code h3="Kod konwersji Java PowerPoint do PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konwersja Microsoft PowerPoint do HTML" %}}

Ponieważ slajdy PowerPoint nie są wyświetlane bezpośrednio na stronach internetowych, istnieje potrzeba konwersji. Programiści mogą załadować plik przy użyciu klasy Presentation, użyć [klasy HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) dla określonych ustawień HTML i wywołać metodę save.

{{% blocks/products/pf/feature-page-code h3="Kod Java do konwersji programu PowerPoint do HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konwersja Microsoft PowerPoint do obrazów" %}}
Formaty Microsoft<sup>®</sup> PowerPoint na obrazy Konwersja JPG, TIFF, PNG itp. jest zwykle wykorzystywana do tworzenia miniatur slajdów, a także w wielu innych przypadkach. Proces kodowania jest prosty. Przejdź przez każdy slajd przez [interfejs ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) po załadowaniu dokumentu, pobierz miniaturę ISlide ISlide.getThumbnail(1f, 1f) do [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html), a następnie zapisz w wymaganym formacie obrazu. 

{{% blocks/products/pf/feature-page-code h3="Kod Java PowerPoint do konwertera obrazów" %}}
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