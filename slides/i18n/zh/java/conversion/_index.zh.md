---
title: 使用 Java 将 Microsoft PowerPoint 演示文稿转换为多个文件
url: /zh/java/conversion/
description: 在基于 Java 的应用程序中将 Microsoft PowerPoint 幻灯片转换为不同的文件，包括 HTML、PDF 和图像格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 进行 Microsoft<sup>®</sup> PowerPoint 演示文稿转换" h2="各种转换场景的Java源代码，将幻灯片转换为图片、HTML、PDF等格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint 库使 Microsoft<sup>®</sup> PowerPoint 演示文稿的转换变得简单且易于自动化流程。开发者可以选择相关场景并集成代码来增强应用功能。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 文件的相互转换" %}}
以编程方式相互转换 Microsoft<sup>®</sup> PowerPoint 文件只是两行代码。使用 [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) 加载文件并调用具有输出文件和 [SaveFormat](https://apireference) 的保存方法.aspose.com/slides/java/com.aspose.slides/SaveFormat）作为参数。

{{% blocks/products/pf/feature-page-code h3="Java 转换代码" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint 到 PDF 转换" %}}

由于 PDF 文件的大量共享，PowerPoint 到 PDF 的转换是一种常见情况。程序员可以自动转换，而不是手动转换，并节省将一堆 PowerPoint 演示文稿转换为 PDF 的时间。演示库提供 [PdfOptions 类](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) 用于自定义特定设置，例如设置文本压缩级别、PDF 合规级别、JPEG 质量、定义行为元文件，转换隐藏的幻灯片，选择选定的幻灯片和生成锁定的密码保护的 PDF 文件。

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint 到 PDF 转换代码" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 到 HTML 转换" %}}

由于 PowerPoint 幻灯片不直接显示在网页上，因此需要转换。程序员可以使用 Presentation 类加载文件，利用 [HtmlOptions 类](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) 进行特定的 HTML 设置并调用 save 方法。

{{% blocks/products/pf/feature-page-code h3="用于 PowerPoint 到 HTML 转换的 Java 代码" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 到图像的转换" %}}
Microsoft<sup>®</sup> PowerPoint 格式到图像 JPG、TIFF、PNG 等的转换通常用于创建幻灯片缩略图以及更多情况。编码过程很简单。加载文档后通过[ISlide接口](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide)遍历每张幻灯片，得到ISlide缩略图ISlide.getThumbnail(1f, 1f)进入[BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) 然后保存成需要的图片格式。 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint 到图像转换器代码" %}}
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