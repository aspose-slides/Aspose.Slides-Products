---
title: Chuyển đổi PDF thành JPG trong PHP
url: /vi/php-java/conversion/pdf-to-jpg/
keywords: PDF sang JPG, Chuyển đổi PDF sang JPG, API PHP, Thư viện PHP, PDF, JPG
description: Chuyển đổi PDF thành JPG trong PHP. Sử dụng PowerPoint PHP API để chuyển đổi các tệp PDF thành JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi PDF thành JPG trong PHP" h2="Thư viện PowerPoint PHP mạnh mẽ giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình chiếu Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi PDF thành JPG trong PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/vi/php-java/) là một thư viện PHP mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi PDF thành JPG. Sử dụng **Aspose.Slides dành cho PHP qua Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp PDF sang JPG chỉ bằng một vài dòng mã PHP.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho PHP xuất tệp PDF sang định dạng tệp JPG một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi PDF thành JPGs và nhiều định dạng tệp khác

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF thành JPG bằng PHP" %}}
Để chuyển đổi PDF sang JPG, bạn cần tạo Bản trình bày từ tệp PDF và lưu dưới dạng JPG.

{{% blocks/products/pf/agp/code-block title="Mã PHP để chuyển đổi PDF thành JPG" offSpacer="true" %}}

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
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi PDF thành JPG bằng API Aspose.Slides cho PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để chuyển đổi PDF thành JPG trong PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides cho PHP qua Java**](https://products.aspose.com/slides/vi/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án PHP của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn PDF bằng PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PDF sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PDF và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}