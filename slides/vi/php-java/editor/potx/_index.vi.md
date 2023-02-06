---
title: Chỉnh sửa POTX trong PHP
url: /vi/php-java/editor/potx/
keywords: Chỉnh sửa POTX, Chỉnh sửa PowerPoint, POTX, PowerPoint, API PHP, Thư viện PHP
description: Chỉnh sửa POTX trong PHP. Sử dụng API thư viện PHP để chỉnh sửa tệp POTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chỉnh sửa POTX trong PHP" h2="Thư viện PHP đa nền tảng và tốc độ cao để chỉnh sửa POTX bằng mã PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Chỉnh sửa POTX bằng Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/vi/php-java/) là một thư viện PHP mạnh mẽ để chỉnh sửa bản trình bày một cách nhanh chóng và dễ dàng. Nó cung cấp cho người dùng một loạt các tính năng để giúp họ tạo các trang trình bày chuyên nghiệp một cách nhanh chóng. Với Aspose, người dùng có thể chỉnh sửa văn bản, thêm hình ảnh, hoạt ảnh và chuyển tiếp vào bản trình bày của họ cũng như áp dụng các tùy chọn định dạng khác nhau như loại phông chữ và lựa chọn màu sắc. Ngoài ra, thư viện cung cấp hỗ trợ cho cả tệp PowerPoint (PPT) và định dạng Bản trình bày OpenOffice (ODP), giúp chia sẻ bản trình bày trên các nền tảng khác nhau dễ dàng hơn bao giờ hết mà không phát sinh bất kỳ sự cố tương thích nào. Bằng cách tận dụng sức mạnh của thư viện Aspose khi tạo hoặc chỉnh sửa bản trình bày tiếp theo của bạn, bạn sẽ chắc chắn rằng các trang trình bày của mình luôn trông tuyệt vời!
Bạn có thể chỉnh sửa tệp POTX bằng cách thêm một dòng văn bản mới vào tệp đó. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chỉnh sửa POTX trong PHP" %}}
Sử dụng [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/vi/php-java/), bạn có thể thêm một dòng văn bản mới vào tài liệu POTX chỉ bằng một vài dòng mã.

{{% blocks/products/pf/agp/code-block title="Mã PHP để chỉnh sửa POTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.potx", SaveFormat::Potx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chỉnh sửa POTX trong PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho PHP qua Java**. Xem [**Cài đặt**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo một thể hiện của lớp Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải bản trình bày POTX mà bạn muốn chỉnh sửa.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm một dòng văn bản mới.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp đã thay đổi.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chỉnh sửa các tệp khác" subTitle="Bạn cũng có thể chỉnh sửa tệp ở các định dạng khác" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}