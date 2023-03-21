---
title: 在 PHP 中將 HTML 轉換為 TIFF
url: /zh-hant/php-java/conversion/html-to-tiff/
keywords: HTML 到 TIFF，將 HTML 轉換為 TIFF，PHP API，PHP 庫，HTML，TIFF
description: 在 PHP 中將 HTML 轉換為 TIFF。使用 PowerPoint PHP API 將 HTML 文件轉換為 TIFF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 PHP 中將 HTML 轉換為 TIFF" h2="強大的 PowerPoint PHP 庫有助於開發應用程序，無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件即可創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 PHP 中將 HTML 轉換為 TIFF" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/) 是一個強大的 PHP 庫，用於創建和操作演示文稿文件。此外，它提供了將 HTML 轉換為 TIFF 的靈活方法。使用**Aspose.Slides for PHP via Java**，任何開發人員或應用程序只需幾行 PHP 代碼即可將 HTML 轉換為 TIFF 文件。

作為現代文檔處理 API，Aspose.Slides for PHP 可快速將 HTML 文件導出為 TIFF 文件格式。 Aspose PowerPoint 庫允許您將 HTML 轉換為 TIFF 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 PHP 將 HTML 轉換為 TIFF" %}}
要將 HTML 轉換為 TIFF，您需要從 HTML 文件創建演示文稿並將其另存為 TIFF。

{{% blocks/products/pf/agp/code-block title="將 HTML 轉換為 TIFF 的 PHP 代碼" offSpacer="true" %}}

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
    $pres->save("output.tiff", SaveFormat::Tiff);        
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for PHP API 將 HTML 轉換為 TIFF" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 PHP 中將 HTML 轉換為 TIFF 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 PHP 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 PHP 中打開源 HTML 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 TIFF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免費在線轉換器" sectionDescription="[如何在 Python 中將 PPT 轉換為 HTML](https://products.aspose.com/slides/zh-hant/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="將 HTML 轉換為其他支持的格式" subTitle="您還可以轉換 HTML 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}