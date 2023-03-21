---
title: Conversione della presentazione di Microsoft PowerPoint in più file utilizzando Java
url: /it/java/conversion/
description: Converti le diapositive di Microsoft PowerPoint in file diversi, inclusi HTML, PDF e formati immagine all'interno di applicazioni basate su Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione di presentazioni PowerPoint di Microsoft<sup>®</sup> tramite Java" h2="Codici sorgente Java per vari scenari di conversione per convertire diapositive in immagini, HTML, PDF e altri formati." >}}

{{% blocks/products/pf/feature-page-summary %}}

La libreria Java PowerPoint ha reso la conversione delle presentazioni Microsoft<sup>®</sup> PowerPoint semplice e facile da automatizzare. Gli sviluppatori possono selezionare lo scenario pertinente e integrare il codice per migliorare la funzionalità dell'applicazione. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversione interna di file Microsoft PowerPoint" %}}
L'interconversione dei file Microsoft<sup>®</sup> PowerPoint a livello di codice è solo un codice di due righe. Carica il file utilizzando [Presentation class](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation) e chiama il metodo di salvataggio con il file di output e [SaveFormat](https://apiference .aspose.com/slides/java/com.aspose.slides/SaveFormat) come parametri.

{{% blocks/products/pf/feature-page-code h3="Codice di conversione Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversione da PowerPoint a PDF" %}}

La conversione da PowerPoint a PDF è un caso comune a causa dell'enorme condivisione di file PDF. Invece delle conversioni manuali, i programmatori possono automatizzarlo e risparmiare tempo per un sacco di presentazioni PowerPoint in PDF. La libreria di presentazione fornisce la [classe PdfOptions](https://apiference.aspose.com/java/slides/com.aspose.slides/PdfOptions) per personalizzare impostazioni specifiche come l'impostazione del livello di compressione del testo, il livello di conformità PDF, la qualità JPEG, definire il comportamento di metafile, conversione di diapositive nascoste, scelta di diapositive selezionate e generazione di file PDF protetti da password bloccati.

{{% blocks/products/pf/feature-page-code h3="Codice di conversione da PowerPoint a PDF da Java" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Conversione da Microsoft PowerPoint a HTML" %}}

Poiché le diapositive di PowerPoint non vengono visualizzate direttamente sulle pagine Web, è necessaria la conversione. I programmatori possono caricare il file utilizzando la classe Presentation, utilizzare la [classe HtmlOptions](https://apiference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) per impostazioni HTML specifiche e invocare il metodo di salvataggio.

{{% blocks/products/pf/feature-page-code h3="Codice Java per la conversione da PowerPoint a HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Conversione da Microsoft PowerPoint a immagini" %}}
La conversione dei formati Microsoft<sup>®</sup> PowerPoint in immagini JPG, TIFF, PNG, ecc. è normalmente per la creazione di miniature di diapositive e molto più casi. Il processo di codifica è semplice. Scorri ogni diapositiva tramite [ISlide interface](https://apiference.aspose.com/slides/java/com.aspose.slides/ISlide) dopo aver caricato il documento, ottieni la miniatura ISlide ISlide.getThumbnail(1f, 1f) in [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) e quindi salvarlo nel formato immagine richiesto. 

{{% blocks/products/pf/feature-page-code h3="Codice Java PowerPoint to Image Converter" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}