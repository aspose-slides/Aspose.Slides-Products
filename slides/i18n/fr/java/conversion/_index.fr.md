---
title: Conversion de présentation Microsoft PowerPoint en plusieurs fichiers à l'aide de Java
url: /fr/java/conversion/
description: Convertissez les diapositives Microsoft PowerPoint en différents fichiers, y compris les formats HTML, PDF et image dans les applications basées sur Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de présentation PowerPoint Microsoft<sup>®</sup> via Java" h2="Codes source Java pour divers scénarios de conversion pour convertir des diapositives en images, HTML, PDF et autres formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

La bibliothèque Java PowerPoint a rendu la conversion des présentations PowerPoint Microsoft<sup>®</sup> simples et faciles à automatiser. Les développeurs peuvent sélectionner le scénario pertinent et intégrer le code pour améliorer la fonctionnalité de l'application. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter-conversion de fichiers Microsoft PowerPoint" %}}
L'interconversion de fichiers Microsoft<sup>®</sup> PowerPoint par programmation n'est qu'un code de deux lignes. Chargez le fichier en utilisant [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) et appelez la méthode save ayant le fichier de sortie et [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) comme paramètres.

{{% blocks/products/pf/feature-page-code h3="Code de conversion Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversion PowerPoint en PDF" %}}

La conversion de PowerPoint en PDF est un cas courant en raison de l'énorme partage de fichiers PDF. Au lieu de conversions manuelles, les programmeurs peuvent l'automatiser et gagner du temps pour un tas de présentations PowerPoint en PDF. La bibliothèque de présentation fournit [classe PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) pour personnaliser des paramètres spécifiques tels que la définition du niveau de compression du texte, le niveau de conformité PDF, la qualité JPEG, définir le comportement de métafichiers, en convertissant les diapositives masquées, en choisissant les diapositives sélectionnées et en générant des fichiers PDF protégés par mot de passe verrouillés.

{{% blocks/products/pf/feature-page-code h3="Code de conversion Java PowerPoint en PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Conversion Microsoft PowerPoint en HTML" %}}

Comme les diapositives PowerPoint ne sont pas directement affichées sur les pages Web, une conversion est donc nécessaire. Les programmeurs peuvent charger un fichier à l'aide de la classe Presentation, utiliser [classe HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) pour des paramètres HTML spécifiques et appeler la méthode save.

{{% blocks/products/pf/feature-page-code h3="Code Java pour la conversion de PowerPoint en HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Conversion de Microsoft PowerPoint en images" %}}
La conversion des formats Microsoft<sup>®</sup> PowerPoint en images JPG, TIFF, PNG, etc. est normalement destinée à la création de miniatures de diapositives ainsi que de bien d'autres cas. Le processus de codage est simple. Parcourez chaque diapositive via [l'interface ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) après avoir chargé le document, obtenez la vignette ISlide ISlide.getThumbnail(1f, 1f) dans [Objet BufferedImage](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html), puis enregistrez-le dans le format d'image requis. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint en code de convertisseur d'image" %}}
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