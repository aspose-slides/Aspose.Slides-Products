---
title: 使用 C# 將 Microsoft PowerPoint 演示文稿轉換為多個文件
url: /zh-hant/net/conversion/
description: 在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上將 Microsoft PowerPoint 幻燈片轉換為不同的文件，包括 PDF、HTML 和圖像格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> 通過 C# 轉換 PowerPoint 演示文稿" h2="用於不同轉換情況的 C# 源代碼，可將文件轉換為圖像、PDF、HTML 和其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

開發人員可以輕鬆快速準確地轉換 Microsoft<sup>®</sup> PowerPoint 演示文稿。立即獲得結果，實現業務流程自動化。我們在這裡討論讀取或加載任何輸入 [支持的 PowerPoint 格式](https://docs.aspose.com/slides/net/supported-file-formats/) 並寫入或保存為任何支持的輸出格式的幾種情況。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 文件的相互轉換" %}}
每當需要自動轉換 Microsoft<sup>®</sup> PowerPoint 格式時。 **C# PowerPoint 庫** 提供了實現此目標的類。使用[Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation)加載文件以加載或讀取所需格式並調用[Save方法](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) 通過指定輸出文件和[SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export) /saveformat).輸出格式。 
{{% blocks/products/pf/feature-page-code h3="用於 Microsoft PowerPoint 演示文稿的 C# 轉換器代碼" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint 到 PDF 轉換" %}}

為了將 PowerPoint 幻燈片準確地轉換為 PDF，程序員可以使用 Presentation 類加載文檔並使用 [PdfOptions 類](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) 進行所有特定和自定義文本壓縮級別、Jpeg 質量、元文件的行為、轉換隱藏幻燈片以及選擇特定幻燈片等選項。甚至可以選擇使用密碼保護轉換後的 PDF 文件。
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint 到 PDF 轉換器代碼" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 到 HTML 轉換" %}}
當需要在網頁中嵌入演示文稿時，就需要將幻燈片轉換為 HTML。 API提供[HtmlOptions類](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions)，加載文件後使用它進行特殊設置，如隱藏幻燈片，默認情況下不會包含在轉換過程中。將最終確定的選項傳遞給 Save 方法進行轉換。
{{% blocks/products/pf/feature-page-code h3="用於 PowerPoint 到 HTML 轉換的 C# 代碼" %}}

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

{{% blocks/products/pf/feature-page-section  h2="將 PowerPoint 幻燈片轉換為圖像格式" %}}
將 Microsoft<sup>®</sup> PowerPoint 格式轉換為圖像 JPEG、PNG、TIFF 等是另一個常見的用例，主要用於創建幻燈片縮略圖。編碼過程很簡單。加載文檔後，使用 [ISlide 界面](https://apireference.aspose.com/net/slides/aspose.slides/islide) 遍歷每張幻燈片。在每次迭代期間，使用 (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] 及其具有自定義圖像尺寸的 GetThumbnail 方法。最後以所需的格式保存圖像。
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint 到圖像轉換器代碼" %}}
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