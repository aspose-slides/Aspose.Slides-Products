---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi POTM sang PNG trong PHP
weight: 1140
url: /vi/php-java/conversion/potm-to-png/ 
keywords: "Convert, PowerPoint, POTM, PNG, Presentation, PHP"
description: Mã mẫu cho chuyển đổi PHP từ POTM sang PNG. Sử dụng PowerPoint PHP API để chuyển đổi hàng loạt tệp POTM sang tệp PNG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi POTM sang PNG trong PHP" h2="Thư viện PHP PowerPoint mạnh mẽ để chuyển đổi POTM sang PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi POTM sang PNG trong PHP" %}}

Bạn cần chuyển đổi tệp POTM thành PNG theo cách lập trình? Sử dụng [* Aspose.Slides cho PHP qua Java *](https://products.aspose.com/slides/vi/php-java/), bất kỳ nhà phát triển nào cũng có thể chuyển đổi định dạng POTM sang PNG chỉ với một vài dòng mã PHP .

Là một API xử lý bản trình bày hiện đại, Aspose.Slides for PHP tạo PNG từ POTM một cách nhanh chóng. Kiểm tra chất lượng của chuyển đổi POTM sang PNG ngay trong [browser] của bạn (https://products.aspose.app/slides/conversion/ppt-to-png). Thư viện Aspose PowerPoint PPTX cho phép bạn chuyển đổi tệp POTM sang nhiều định dạng phổ biến.

Bạn có thể cài đặt thư viện từ [Composer](https://packagist.org/packages/aspose/slides) bằng lệnh sau:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bảng điều khiển / Thiết bị đầu cuối" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lưu POTM dưới dạng PNG trong PHP" %}}

Sử dụng ứng dụng miễn phí để xem trình diễn về quá trình chuyển đổi POTM sang PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã mẫu này hiển thị Chuyển đổi PHP từ POTM sang PNG" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
    }
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi POTM sang PNG trong PHP" intro="Đây là các bước để chuyển đổi tệp POTM thành PNG bằng PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp POTM bằng một phiên bản của lớp Trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat. {To_format} làm tham số{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tệp POTM sẽ được lưu tại đường dẫn được chỉ định{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="yêu cầu hệ thống" intro="Trước khi chạy mã nguồn mẫu chuyển đổi PHP, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt PHP 7, thêm đường dẫn đến PHP vào biến hệ thống `PATH` và đặt` allow_url_include` thành `On` trong tệp` php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt JRE 8. Đặt biến môi trường `JAVA_HOME` làm đường dẫn đến vị trí JRE đã cài đặt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt Apache Tomcat 8.0 (xem [thêm](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POTM to PNG"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi POTM sang nhiều định dạng tệp khác. Xem các chuyển đổi được hỗ trợ khác bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Hình ảnh bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="Bản trình bày XML phẳng OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="Định dạng trao đổi đồ họa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="Hình ảnh JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-odp/" name="POTM TO ODP" description="Định dạng bản trình bày OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="Định dạng chuẩn OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Định dạng tài liệu di động" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Trình chiếu hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Định dạng bản trình bày XML mở" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="Đồ họa vector có thể mở rộng" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="Định dạng SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
