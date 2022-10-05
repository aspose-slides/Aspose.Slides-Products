---
title: Microsoft PowerPoint Presentation Conversion to Multiple Files using Java 
url: /java/conversion/
description: Convert Microsoft PowerPoint Slides to different files including HTML, PDF and image formats within Java based applications.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> PowerPoint Presentation Conversion in Java" h2="Java source codes for various conversion scenarios to convert slides to images, HTML, PDF and other formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint library has made the conversion of Microsoft<sup>&reg;</sup> PowerPoint Presentations simple and easy to automate processes. Developers can select the relevant scenario and integrate the code to enhance the application functionality. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter Conversion Of Microsoft PowerPoint Files" %}}
Interconversion of Microsoft<sup>&reg;</sup> PowerPoint files programmatically is just a two lines code. Load the file using [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) and call the save method having the output file and [SaveFormat](https://apireference.aspose.com/slides/java/com.aspose.slides/SaveFormat) as parameters.

{{% blocks/products/pf/feature-page-code h3="Java Conversion Code" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint to PDF Conversion" %}}

PowerPoint to PDF conversion is a common case due the huge sharing of PDF files. Instead of manual conversions, programmers can automate it and save time for bunch of PowerPoint presentations to PDF. Presentation library provides [PdfOptions class](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) for customizing specific settings like setting text compression level, PDF compliance level, JPEG quality, define the behavior of metafiles, converting hidden slides, choosing selected slides and generating locked password protected PDF files.

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint to PDF Conversion Code" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Mircrosoft PowerPoint to HTML Conversion" %}}

As PowerPoint slides are not directly displayed on webpages so there is need of conversion. Programmers can load file using Presentation class, utilize [HtmlOptions class](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) for specific HTML settings and invoke the save method.

{{% blocks/products/pf/feature-page-code h3="Java code for PowerPoint to HTML Conversion" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint to Images Conversion" %}}
Microsoft<sup>&reg;</sup> PowerPoint formats to images JPG, TIFF, PNG, etc conversion is normally for creating slides thumbnails as well as much more cases. Coding process is simple. Iterate through each slide via [ISlide interface](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) after loading the document, get the ISlide thumbnail ISlide.getThumbnail(1f, 1f) into [BufferedImage  Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) and then save into the required image format. 

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