---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi JPG thành Image trong PHP
url: /vi/php-java/conversion/jpg-to-image/
keywords: JPG sang Image, Chuyển đổi JPG sang Image, API PHP, Thư viện PHP, JPG, Image
description: Chuyển đổi JPG thành Image trong PHP. Sử dụng PowerPoint PHP API để chuyển đổi các tệp JPG thành Image
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi JPG thành Image trong PHP" h2="Thư viện PowerPoint PHP mạnh mẽ giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình chiếu Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi JPG thành Image bằng PHP" variant="code" %}}

Để chuyển đổi JPG sang Image, bạn cần tạo Bản trình bày từ tệp JPG và lưu dưới dạng Image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã PHP để chuyển đổi JPG thành Image" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi JPG thành Image trong PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/vi/php-java/) là một thư viện PHP mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi JPG thành Image. Sử dụng **Aspose.Slides dành cho PHP qua Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp JPG sang Image chỉ bằng một vài dòng mã PHP.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho PHP xuất tệp JPG sang định dạng tệp Image một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi JPG thành Images và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi JPG thành Image bằng API Aspose.Slides cho PHP" intro="Đây là các bước để chuyển đổi JPG thành Image trong PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides cho PHP qua Java**](https://products.aspose.com/slides/vi/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án PHP của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp nguồn JPG bằng PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp Image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Được xây dựng bằng Aspose.Slides" title="Chuyển đổi JPG sang Hình ảnh trực tuyến" description="Ứng dụng Aspose.Slides Conversion miễn phí được xây dựng bằng [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/vi/php-java/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp JPG của riêng bạn." button="Mở Aspose.Slides Conversion" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" upload="Thả hoặc tải lên tệp của bạn" saveAs="Lưu dưới dạng" convert="Chuyển đổi" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides chuyển đổi tệp trước khi bạn viết mã.
- Tải lên các tệp JPG và lưu chúng dưới dạng Hình ảnh.
- Tải xuống kết quả hoặc chuyển đổi thêm tệp.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi JPG sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi JPG và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
