---
title: Chuyển đổi SVG thành PPTX trong PHP
url: /vi/php-java/conversion/svg-to-pptx/
keywords: SVG sang PPTX, Chuyển đổi SVG sang PPTX, API PHP, Thư viện PHP, SVG, PPTX
description: Chuyển đổi SVG thành PPTX trong PHP. Sử dụng PowerPoint PHP API để chuyển đổi các tệp SVG thành PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi SVG thành PPTX trong PHP" h2="Thư viện PowerPoint PHP mạnh mẽ giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình chiếu Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi SVG thành PPTX trong PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/vi/php-java/) là một thư viện PHP mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi SVG thành PPTX. Sử dụng **Aspose.Slides dành cho PHP qua Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp SVG sang PPTX chỉ bằng một vài dòng mã PHP.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho PHP xuất tệp SVG sang định dạng tệp PPTX một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi SVG thành PPTXs và nhiều định dạng tệp khác

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi SVG thành PPTX bằng PHP" %}}
Để chuyển đổi SVG sang PPTX, bạn cần tạo Bản trình bày từ tệp SVG và lưu dưới dạng PPTX.

{{% blocks/products/pf/agp/code-block title="Mã PHP để chuyển đổi SVG thành PPTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.svg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $svgImage = new SvgImage($contents);
    $image = $pres->getImages()->addImage($svgImage);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi SVG thành PPTX bằng API Aspose.Slides cho PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để chuyển đổi SVG thành PPTX trong PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides cho PHP qua Java**](https://products.aspose.com/slides/vi/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án PHP của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn SVG bằng PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Chuyển đổi trực tuyến miễn phí" sectionDescription="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi SVG sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi SVG và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}