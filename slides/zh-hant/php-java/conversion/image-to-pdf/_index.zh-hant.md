---
title: 在 PHP 中將 Image 轉換為 PDF
url: /zh-hant/php-java/conversion/image-to-pdf/
keywords: Image 到 PDF，將 Image 轉換為 PDF，PHP API，PHP 庫，Image，PDF
description: 在 PHP 中將 Image 轉換為 PDF。使用 PowerPoint PHP API 將 Image 文件轉換為 PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 PHP 中將 Image 轉換為 PDF" h2="強大的 PowerPoint PHP 庫有助於開發應用程序，無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件即可創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 PHP 中將 Image 轉換為 PDF" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/) 是一個強大的 PHP 庫，用於創建和操作演示文稿文件。此外，它提供了將 Image 轉換為 PDF 的靈活方法。使用**Aspose.Slides for PHP via Java**，任何開發人員或應用程序只需幾行 PHP 代碼即可將 Image 轉換為 PDF 文件。

作為現代文檔處理 API，Aspose.Slides for PHP 可快速將 Image 文件導出為 PDF 文件格式。 Aspose PowerPoint 庫允許您將 Image 轉換為 PDF 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 PHP 將 Image 轉換為 PDF" %}}
要將 Image 轉換為 PDF，您需要從 Image 文件創建演示文稿並將其另存為 PDF。

{{% blocks/products/pf/agp/code-block title="將 Image 轉換為 PDF 的 PHP 代碼" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for PHP API 將 Image 轉換為 PDF" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 PHP 中將 Image 轉換為 PDF 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 PHP 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 PHP 中打開源 Image 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 Image 轉換為其他支持的格式" subTitle="您還可以轉換 Image 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}