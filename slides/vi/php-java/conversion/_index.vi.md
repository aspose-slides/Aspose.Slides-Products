---
title: Chuyển đổi bản trình bày Microsoft PowerPoint sang PDF trong PHP
url: /vi/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: API PHP để chuyển đổi PPT sang PDF. Chuyển đổi bản trình bày sang JPG, PNG và các định dạng khác trong PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> Bản trình bày PowerPoint sang Chuyển đổi PDF trong PHP" h2="Mã nguồn PHP cho các trường hợp chuyển đổi khác nhau để chuyển đổi PPT sang PDF, PNG, HTML, JPEG, PPTX và các định dạng khác." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides cho PHP qua Java](https://products.aspose.com/slides/vi/php-java/) là một thư viện lớp tại chỗ mạnh mẽ được sử dụng để xử lý và làm việc với các bản trình bày. Các nhà phát triển có thể dễ dàng chuyển đổi PowerPoint sang PDF với tốc độ và độ chính xác cao. Nhận kết quả ngay lập tức để tự động hóa các quy trình kinh doanh. Chúng tôi đang thảo luận ở đây một số trường hợp để đọc hoặc tải bất kỳ đầu vào nào [các định dạng PowerPoint được hỗ trợ](https://docs.aspose.com/slides/php-java/supported-file-formats/) và ghi hoặc lưu vào bất kỳ định dạng đầu ra nào được hỗ trợ . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PowerPoint sang PDF trong PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/vi/php-java/) cho phép bạn chuyển đổi các tệp ở định dạng PowerPoint PPT, PPTX và OpenOffice ODP sang PDF. Để chuyển đổi bản trình bày sang PDF, chỉ cần chuyển tên tệp và định dạng lưu vào phương thức `Presentation.save`. Lớp `Presentation` cho thấy phương thức` save` có thể được gọi để chuyển đổi toàn bộ bản trình bày PPT, PPTX hoặc ODP thành tài liệu PDF.

{{% blocks/products/pf/feature-page-code h3="Chuyển đổi PHP PowerPoint sang PDF" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF sang PPT trong PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/vi/php-java/) cho phép bạn nhập bản trình bày từ PDF. Về cơ bản, bạn có thể chuyển đổi một tệp PDF sang một bản trình bày PowerPoint. Để chuyển đổi PDF sang Powerpoint, hãy thực hiện theo các bước sau:
- Khởi tạo một đối tượng của lớp `Presentation`.
- Gọi phương thức `addFromPdf` và chuyển tệp PDF.
- Sử dụng phương thức `save` để lưu tệp ở định dạng PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Chuyển đổi PDF sang Powerpoint trong PHP" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPT sang PDF với các tùy chọn tùy chỉnh trong PHP" %}}

Để chuyển đổi chính xác các slide PowerPoint sang PDF, Lập trình viên có thể tải tài liệu bằng lớp `Presentation` và sử dụng lớp` PdfOptions` cho tất cả các tùy chọn cụ thể và tùy chỉnh như mức độ nén văn bản, chất lượng Jpeg, hoạt động của siêu tệp, chuyển đổi các trang trình bày ẩn cũng như lựa chọn các trang trình bày cụ thể và hơn thế nữa. Thậm chí có tùy chọn để bảo vệ tệp PDF đã chuyển đổi bằng mật khẩu.
{{% blocks/products/pf/feature-page-code h3="Chuyển đổi PHP PowerPoint sang PDF với cài đặt tùy chỉnh" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft PowerPoint sang HTML trong PHP" %}}
Khi nào có nhu cầu nhúng các bản trình bày trong các trang web, thì cần phải chuyển đổi các trang trình bày sang HTML. 
{{% blocks/products/pf/feature-page-code h3="Mã PHP cho Chuyển đổi PowerPoint sang HTML" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PowerPoint sang JPG" %}}
Chuyển đổi định dạng Microsoft <sup> ® </sup> PowerPoint sang hình ảnh JPEG, PNG, TIFF, v.v. là một trường hợp sử dụng phổ biến khác, hầu hết được sử dụng để tạo hình thu nhỏ của trang chiếu. 
{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi PHP PPT sang JPG" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>  
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}