---
title: 在 PHP 中合併 PDF 文件
url: /zh-hant/php-java/merger/pdf-to-pdf/
keywords: 合併 PDF、PDF 到 PDF、合併 PDF、合併 PDF、PHP API、PHP 庫
description: 在 PHP 中將 PDF 合併為 PDF。使用 PHP 庫 API 合併 PDF 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 PHP 中合併 PDF" h2="用於使用 PHP 代碼合併 PDF 文件的高速跨平台 PHP 庫" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 將 PDF 合併為 PDF" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/) 是一個功能強大的 PHP 庫，用於創建、轉換、合併和操作演示文稿、PDF、和其他文件。將 PDF 合併為 PDF 時，實際上是將 2 個文檔的頁面合併為一個 PDF 文件。 Aspose.Slides 允許您以不同的方式合併 PDF。您可以合併 PDF 及其所有形狀、樣式、文本、格式等。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 PHP 中將 PDF 合併為 PDF" %}}
使用 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/)，只需幾行代碼即可快速合併 PDF 文件

{{% blocks/products/pf/agp/code-block title="將 PDF 合併為 PDF 的 PHP 代碼" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $pres->getSlides()->addFromPdf("document1.pdf");
    $pres->getSlides()->addFromPdf("document2.pdf");

    $pres->save("merged-pdf.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 PHP 中合併 PDF" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
通過 Java 安裝 **Aspose.Slides for PHP**。請參閱 [**安裝**](https://docs.aspose.com/slides/php-java/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加庫作為項目中的引用。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建一個 Presentation 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要合併的 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 PDF。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="合併其他文件" subTitle="您還可以合併其他格式的文件以獲得單個文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}