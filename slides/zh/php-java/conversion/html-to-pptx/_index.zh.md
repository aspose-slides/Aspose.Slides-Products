---
title: 在 PHP 中将 HTML 转换为 PPTX
url: /zh/php-java/conversion/html-to-pptx/
keywords: HTML 到 PPTX，将 HTML 转换为 PPTX，PHP API，PHP 库，HTML，PPTX
description: 在 PHP 中将 HTML 转换为 PPTX。使用 PowerPoint PHP API 将 HTML 文件转换为 PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 PHP 中将 HTML 转换为 PPTX" h2="强大的 PowerPoint PHP 库有助于开发应用程序，无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件即可创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 PHP 中将 HTML 转换为 PPTX" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh/php-java/) 是一个强大的 PHP 库，用于创建和操作演示文稿文件。此外，它提供了将 HTML 转换为 PPTX 的灵活方法。使用**Aspose.Slides for PHP via Java**，任何开发人员或应用程序只需几行 PHP 代码即可将 HTML 转换为 PPTX 文件。

作为现代文档处理 API，Aspose.Slides for PHP 可快速将 HTML 文件导出为 PPTX 文件格式。 Aspose PowerPoint 库允许您将 HTML 转换为 PPTX 和许多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 PHP 将 HTML 转换为 PPTX" %}}
要将 HTML 转换为 PPTX，您需要从 HTML 文件创建演示文稿并将其另存为 PPTX。

{{% blocks/products/pf/agp/code-block title="将 HTML 转换为 PPTX 的 PHP 代码" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for PHP API 将 HTML 转换为 PPTX" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是在 PHP 中将 HTML 转换为 PPTX 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh/php-java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 PHP 项目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 PHP 中打开源 HTML 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将结果保存为 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="将 HTML 转换为其他支持的格式" subTitle="您还可以转换 HTML 并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}