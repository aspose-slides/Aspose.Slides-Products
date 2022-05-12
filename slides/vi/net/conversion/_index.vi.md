---
title: Chuyển đổi bản trình bày Microsoft PowerPoint sang nhiều tệp bằng C #
url: /vi/net/conversion/
description: Chuyển đổi Microsoft PowerPoint Slides sang các tệp khác nhau bao gồm các định dạng PDF, HTML và hình ảnh trên .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> Chuyển đổi bản trình bày PowerPoint qua C #" h2="Mã nguồn C # cho các trường hợp chuyển đổi khác nhau để chuyển đổi tệp sang hình ảnh, PDF, HTML và các định dạng khác." >}}

{{% blocks/products/pf/feature-page-summary %}}

Các nhà phát triển có thể dễ dàng chuyển đổi các Bản trình bày PowerPoint của Microsoft <sup> ® </sup> với tốc độ và độ chính xác. Nhận kết quả ngay lập tức để tự động hóa các quy trình kinh doanh. Chúng tôi đang thảo luận ở đây một số trường hợp để đọc hoặc tải bất kỳ đầu vào nào [các định dạng PowerPoint được hỗ trợ](https://docs.aspose.com/slides/net/supported-file-formats/) và ghi hoặc lưu vào bất kỳ định dạng đầu ra nào được hỗ trợ. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi giữa các tệp Microsoft PowerPoint" %}}
Bất cứ khi nào cần tự động chuyển đổi giữa các định dạng Microsoft <sup> ® </sup> PowerPoint. ** Thư viện C # PowerPoint ** cung cấp các lớp để đạt được mục tiêu này. Tải tệp bằng [Lớp trình bày](https://apireference.aspose.com/net/slides/aspose.slides/presentation) để tải hoặc đọc định dạng mong muốn và gọi [Phương thức lưu](https://apireference). aspose.com/slides/net/aspose.slides/presentation/methods/save) của cùng một lớp bằng cách chỉ định tệp đầu ra và [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi C # cho bản trình bày Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi C # PowerPoint sang PDF" %}}

Để chuyển đổi chính xác các trang chiếu PowerPoint sang PDF, Lập trình viên có thể tải tài liệu bằng lớp Trình bày và sử dụng [lớp PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) cho tất cả các tùy chỉnh và cụ thể các tùy chọn như mức độ nén văn bản, chất lượng Jpeg, hoạt động của siêu tệp, chuyển đổi các trang trình bày ẩn cũng như chọn các trang trình bày cụ thể và hơn thế nữa. Thậm chí có tùy chọn để bảo vệ tệp PDF đã chuyển đổi bằng mật khẩu.
{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi C # PowerPoint sang PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft PowerPoint sang HTML" %}}
Khi nào có nhu cầu nhúng các bản trình bày trong các trang web, thì cần phải chuyển đổi các trang trình bày sang HTML. API cung cấp [lớp HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), Sử dụng nó sau khi tải các tệp cho các cài đặt đặc biệt như trang trình bày ẩn, theo mặc định, các trang này sẽ không được bao gồm trong quá trình chuyển đổi. Chuyển các tùy chọn cuối cùng đến phương pháp Lưu để chuyển đổi.
{{% blocks/products/pf/feature-page-code h3="Mã C # cho Chuyển đổi PowerPoint sang HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Trang trình bày PowerPoint sang Định dạng Hình ảnh" %}}
Chuyển đổi định dạng Microsoft <sup> ® </sup> PowerPoint sang hình ảnh JPEG, PNG, TIFF, v.v. là một trường hợp sử dụng phổ biến khác được sử dụng chủ yếu để tạo hình thu nhỏ của trang chiếu. Quá trình mã hóa rất đơn giản. Sau khi tải tài liệu, Sử dụng [giao diện ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide) để lặp qua từng trang trình bày. Trong mỗi lần lặp, hãy sử dụng (Đối tượng Bitmap) [https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] cùng với mehtod GetThumbnail của nó có kích thước hình ảnh tùy chỉnh. Cuối cùng lưu ảnh ở định dạng yêu cầu.
{{% blocks/products/pf/feature-page-code h3="C # PowerPoint to Image Converter Code" %}}
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