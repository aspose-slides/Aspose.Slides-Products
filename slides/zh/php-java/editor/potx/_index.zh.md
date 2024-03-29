---
title: 在 PHP 中编辑 POTX
url: /zh/php-java/editor/potx/
keywords: 编辑 POTX、编辑 PowerPoint、POTX、PowerPoint、PHP API、PHP 库
description: 在 PHP 中编辑 POTX。使用 PHP 库 API 编辑 POTX 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 PHP 中编辑 POTX" h2="用于使用 PHP 代码编辑 POTX 的高速跨平台 PHP 库" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 编辑 POTX" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh/php-java/) 是一个功能强大的 PHP 库，可快速轻松地编辑演示文稿。它为用户提供了广泛的功能，可帮助他们立即创建具有专业外观的幻灯片。使用 Aspose，用户可以编辑文本、添加图像、动画和过渡到他们的演示文稿，以及应用各种格式选项，如字体类型和颜色选择。此外，该库还支持 PowerPoint (PPT) 文件和 OpenOffice Presentation (ODP) 格式，这使得跨不同平台共享演示文稿比以往任何时候都更容易，而不会出现任何兼容性问题。通过在创建或编辑您的下一个演示文稿时利用 Aspose 库的强大功能，您将确保您的幻灯片每次看起来都很棒！
您可以通过向其中添加新的文本行来编辑 POTX 文件。 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 PHP 中编辑 POTX" %}}
使用 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh/php-java/)，您可以向 POTX 文档添加一行新文本，只需几行代码。

{{% blocks/products/pf/agp/code-block title="用于编辑 POTX 的 PHP 代码" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="如何在 PHP 中编辑 POTX" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
通过 Java 安装 **Aspose.Slides for PHP**。请参阅 [**安装**](https://docs.aspose.com/slides/php-java/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库添加为项目中的参考。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建一个 Presentation 类的实例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加载您要编辑的 POTX 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改的文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}