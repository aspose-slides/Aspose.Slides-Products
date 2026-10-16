---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PPT sang PDF trong PHP
weight: 2180
url: /vi/php-java/conversion/ppt-to-pdf/ 
keywords: "Convert, PowerPoint, PPT, PDF, Presentation, PHP"
description: Mã mẫu cho chuyển đổi PHP từ PPT sang PDF. Sử dụng PowerPoint PHP API để chuyển đổi hàng loạt tệp PPT sang tệp PDF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PPT sang PDF trong PHP" h2="Thư viện PHP PowerPoint mạnh mẽ để chuyển đổi PPT sang PDF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PPT sang PDF trong PHP" %}}

Bạn cần chuyển đổi tệp PPT thành PDF theo cách lập trình? Sử dụng [* Aspose.Slides cho PHP qua Java *](https://products.aspose.com/slides/vi/php-java/), bất kỳ nhà phát triển nào cũng có thể chuyển đổi định dạng PPT sang PDF chỉ với một vài dòng mã PHP .

Là một API xử lý bản trình bày hiện đại, Aspose.Slides for PHP tạo PDF từ PPT một cách nhanh chóng. Kiểm tra chất lượng của chuyển đổi PPT sang PDF ngay trong [browser] của bạn (https://products.aspose.app/slides/conversion). Thư viện Aspose PowerPoint PPTX cho phép bạn chuyển đổi tệp PPT sang nhiều định dạng phổ biến.

Bạn có thể cài đặt thư viện từ [Composer](https://packagist.org/packages/aspose/slides) bằng lệnh sau:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bảng điều khiển / Thiết bị đầu cuối" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lưu PPT dưới dạng PDF trong PHP" %}}

Sử dụng ứng dụng miễn phí để xem trình diễn về quá trình chuyển đổi PPT sang PDF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã mẫu này hiển thị Chuyển đổi PHP từ PPT sang PDF" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi PPT sang PDF trong PHP" intro="Đây là các bước để chuyển đổi tệp PPT thành PDF bằng PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPT bằng một phiên bản của lớp Trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat. {To_format} làm tham số{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tệp PPT sẽ được lưu tại đường dẫn được chỉ định{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="yêu cầu hệ thống" intro="Trước khi chạy mã nguồn mẫu chuyển đổi PHP, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt PHP 7, thêm đường dẫn đến PHP vào biến hệ thống `PATH` và đặt` allow_url_include` thành `On` trong tệp` php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt JRE 8. Đặt biến môi trường `JAVA_HOME` làm đường dẫn đến vị trí JRE đã cài đặt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt Apache Tomcat 8.0 (xem [thêm](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPT to PDF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPT sang nhiều định dạng tệp khác. Xem các chuyển đổi được hỗ trợ khác bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Hình ảnh bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-fodp/" name="PPT TO FODP" description="Bản trình bày XML phẳng OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-gif/" name="PPT TO GIF" description="Định dạng trao đổi đồ họa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-html/" name="PPT TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-jpg/" name="PPT TO JPG" description="Hình ảnh JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-odp/" name="PPT TO ODP" description="Định dạng bản trình bày OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-otp/" name="PPT TO OTP" description="Định dạng chuẩn OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-png/" name="PPT TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pot/" name="PPT TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-potm/" name="PPT TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-potx/" name="PPT TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pps/" name="PPT TO PPS" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Trình chiếu hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Định dạng bản trình bày XML mở" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-svg/" name="PPT TO SVG" description="Đồ họa vector có thể mở rộng" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-swf/" name="PPT TO SWF" description="Định dạng SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-xps/" name="PPT TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
