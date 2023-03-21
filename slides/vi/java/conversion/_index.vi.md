---
title: Chuyển đổi bản trình bày Microsoft PowerPoint sang nhiều tệp bằng Java
url: /vi/java/conversion/
description: Chuyển đổi các Trang trình bày Microsoft PowerPoint sang các tệp khác nhau bao gồm định dạng HTML, PDF và hình ảnh trong các ứng dụng dựa trên Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> Chuyển đổi bản trình bày PowerPoint qua Java" h2="Mã nguồn Java cho các tình huống chuyển đổi khác nhau để chuyển đổi các trang trình bày sang hình ảnh, HTML, PDF và các định dạng khác." >}}

{{% blocks/products/pf/feature-page-summary %}}

Thư viện Java PowerPoint đã làm cho việc chuyển đổi Bản trình bày PowerPoint của Microsoft <sup> ® </sup> trở nên đơn giản và dễ dàng để tự động hóa các quy trình. Các nhà phát triển có thể chọn kịch bản phù hợp và tích hợp mã để nâng cao chức năng ứng dụng. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi giữa các tệp Microsoft PowerPoint" %}}
Chuyển đổi giữa các tệp Microsoft <sup> ® </sup> PowerPoint theo chương trình chỉ là một đoạn mã hai dòng. Tải tệp bằng [Lớp trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) và gọi phương thức lưu có tệp đầu ra và [SaveFormat](https: // apireference .aspose.com / slides / java / com.aspose.slides / SaveFormat) dưới dạng tham số.

{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PowerPoint sang PDF" %}}

Chuyển đổi PowerPoint sang PDF là một trường hợp phổ biến do sự chia sẻ rất lớn của các tệp PDF. Thay vì chuyển đổi thủ công, các lập trình viên có thể tự động hóa nó và tiết kiệm thời gian cho nhiều bài thuyết trình PowerPoint sang PDF. Thư viện bản trình bày cung cấp [lớp PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) để tùy chỉnh các cài đặt cụ thể như đặt mức nén văn bản, mức tuân thủ PDF, chất lượng JPEG, xác định hành vi của siêu tệp, chuyển đổi các trang trình bày ẩn, chọn các trang trình bày đã chọn và tạo các tệp PDF được bảo vệ bằng mật khẩu bị khóa.

{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi Java PowerPoint sang PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft PowerPoint sang HTML" %}}

Vì các slide PowerPoint không được hiển thị trực tiếp trên các trang web nên cần phải chuyển đổi. Lập trình viên có thể tải tệp bằng lớp Trình bày, sử dụng [lớp HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) cho các cài đặt HTML cụ thể và gọi phương thức lưu.

{{% blocks/products/pf/feature-page-code h3="Mã Java cho Chuyển đổi PowerPoint sang HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft PowerPoint sang Hình ảnh" %}}
Microsoft <sup> ® </sup> Định dạng PowerPoint sang hình ảnh JPG, TIFF, PNG, v.v. Việc chuyển đổi thường để tạo hình thu nhỏ trang chiếu cũng như nhiều trường hợp khác. Quá trình mã hóa rất đơn giản. Lặp lại từng trang chiếu qua [giao diện ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) sau khi tải tài liệu, lấy ISlide thumbnail ISlide.getThumbnail (1f, 1f) vào [Đối tượng BufferedImage](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) và sau đó lưu vào định dạng hình ảnh yêu cầu. 

{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi Java PowerPoint sang Hình ảnh" %}}
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