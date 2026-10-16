---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi HTML thành Image trong PHP
url: /vi/php-java/conversion/html-to-image/
keywords: HTML sang Image, Chuyển đổi HTML sang Image, API PHP, Thư viện PHP, HTML, Image
description: Chuyển đổi HTML thành Image trong PHP. Sử dụng PowerPoint PHP API để chuyển đổi các tệp HTML thành Image
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi HTML thành Image trong PHP" h2="Thư viện PowerPoint PHP mạnh mẽ giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình chiếu Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi HTML thành Image bằng PHP" variant="code" %}}

Để chuyển đổi HTML sang Image, bạn cần tạo Bản trình bày từ tệp HTML và lưu dưới dạng Image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã PHP để chuyển đổi HTML thành Image" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
        
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename = 'file.html';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $pres->getSlides()->addFromHtml($contents);        
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi HTML thành Image trong PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/vi/php-java/) là một thư viện PHP mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi HTML thành Image. Sử dụng **Aspose.Slides dành cho PHP qua Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp HTML sang Image chỉ bằng một vài dòng mã PHP.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho PHP xuất tệp HTML sang định dạng tệp Image một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi HTML thành Images và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi HTML thành Image bằng API Aspose.Slides cho PHP" intro="Đây là các bước để chuyển đổi HTML thành Image trong PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides cho PHP qua Java**](https://products.aspose.com/slides/vi/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án PHP của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp nguồn HTML bằng PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp Image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Chuyển đổi trực tuyến miễn phí"
  description="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi HTML sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi HTML và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
