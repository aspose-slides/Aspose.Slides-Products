---
title: 使用 C# 将 Microsoft PowerPoint 演示文稿转换为多个文件
url: /zh/net/conversion/
description: 在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上将 Microsoft PowerPoint 幻灯片转换为不同的文件，包括 PDF、HTML 和图像格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> 通过 C# 转换 PowerPoint 演示文稿" h2="用于不同转换情况的 C# 源代码，可将文件转换为图像、PDF、HTML 和其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

开发人员可以轻松快速准确地转换 Microsoft<sup>®</sup> PowerPoint 演示文稿。立即获得结果，实现业务流程自动化。我们在这里讨论读取或加载任何输入 [支持的 PowerPoint 格式](https://docs.aspose.com/slides/net/supported-file-formats/) 并写入或保存为任何支持的输出格式的几种情况。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 文件的相互转换" %}}
每当需要自动转换 Microsoft<sup>®</sup> PowerPoint 格式时。 **C# PowerPoint 库** 提供了实现此目标的类。使用[Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation)加载文件以加载或读取所需格式并调用[Save方法](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) 通过指定输出文件和[SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export) /saveformat).输出格式。 
{{% blocks/products/pf/feature-page-code h3="用于 Microsoft PowerPoint 演示文稿的 C# 转换器代码" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint 到 PDF 转换" %}}

为了将 PowerPoint 幻灯片准确地转换为 PDF，程序员可以使用 Presentation 类加载文档并使用 [PdfOptions 类](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) 进行所有特定和自定义文本压缩级别、Jpeg 质量、元文件的行为、转换隐藏幻灯片以及选择特定幻灯片等选项。甚至可以选择使用密码保护转换后的 PDF 文件。
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint 到 PDF 转换器代码" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 到 HTML 转换" %}}
当需要在网页中嵌入演示文稿时，就需要将幻灯片转换为 HTML。 API提供[HtmlOptions类](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions)，加载文件后使用它进行特殊设置，如隐藏幻灯片，默认情况下不会包含在转换过程中。将最终确定的选项传递给 Save 方法进行转换。
{{% blocks/products/pf/feature-page-code h3="用于 PowerPoint 到 HTML 转换的 C# 代码" %}}

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

{{% blocks/products/pf/feature-page-section  h2="将 PowerPoint 幻灯片转换为图像格式" %}}
将 Microsoft<sup>®</sup> PowerPoint 格式转换为图像 JPEG、PNG、TIFF 等是另一个常见的用例，主要用于创建幻灯片缩略图。编码过程很简单。加载文档后，使用 [ISlide 界面](https://apireference.aspose.com/net/slides/aspose.slides/islide) 遍历每张幻灯片。在每次迭代期间，使用 (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] 及其具有自定义图像尺寸的 GetThumbnail 方法。最后以所需格式保存图像。
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint 到图像转换器代码" %}}
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