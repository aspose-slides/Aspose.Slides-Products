---
title: Microsoft PowerPoint Presentation Conversion to Multiple Files using C# 
url: /net/conversion/
description: Convert Microsoft PowerPoint Slides to different files including PDF, HTML and image formats on .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> PowerPoint Presentation Conversion in C#" h2="C# Source Codes for different conversion cases to convert files to images, PDF, HTML and other formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

It is easy for the developers to convert Microsoft<sup>&reg;</sup> PowerPoint Presentations with speed and accuracy. Get the results within no time for automating the business processes. We are discussing here few cases to read or load any input [supported PowerPoint formats](https://docs.aspose.com/slides/net/supported-file-formats/) and write or save to any supported output format. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter Conversion Of Microsoft PowerPoint Files" %}}
Whenever there is need to automate the inter conversion of Microsoft<sup>&reg;</sup> PowerPoint formats. **C# PowerPoint library** provides classes to achieve this target. Load the file using [Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation) to load or read the desired format and calling the [Save method](https://apireference.aspose.com/slides/net/aspose.slides/presentation/methods/save) of same class by specifying the output file and [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export/saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="C# Converter Code for Microsoft PowerPoint Presentations" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint to PDF Conversion" %}}

For converting PowerPoint slides to PDF accurately, Programmers can load the document using Presentation class and use [PdfOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) for all specific and custom options like text compression level, Jpeg quality, the behavior of metafiles, converting hidden slides as well as selecting specific slides and more. Even there is option to protect the converted PDF file with password.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint to PDF Converter Code" %}}

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
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Mircrosoft PowerPoint to HTML Conversion" %}}
When ever there is need to embed presentations within webpages, then there is need to convert slides to HTML. API provides [HtmlOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), Use it after loading the files for special settings like hidden slides, as by default, these will not be included during conversion process. Pass the finalized options to Save method for conversion.
{{% blocks/products/pf/feature-page-code h3="C# Code for PowerPoint to HTML Conversion" %}}

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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint Slides to Image Formats" %}}
Converting Microsoft<sup>&reg;</sup> PowerPoint formats to images JPEG, PNG, TIFF etc is another commom use case mostly used for creating slides thumbnails. Coding process is simple. After loading the document, Use [ISlide interface](https://apireference.aspose.com/net/slides/aspose.slides/islide) to iterate through each slide. During each iteration, use (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] along with its GetThumbnail mehtod having customized image dimensions. Finally save the image in the required format.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint to Image Converter Code" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}