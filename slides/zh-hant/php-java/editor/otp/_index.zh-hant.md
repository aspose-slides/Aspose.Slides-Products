---
title: 在 PHP 中編輯 OTP
url: /zh-hant/php-java/editor/otp/
keywords: 編輯 OTP、編輯 PowerPoint、OTP、PowerPoint、PHP API、PHP 庫
description: 在 PHP 中編輯 OTP。使用 PHP 庫 API 編輯 OTP 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 PHP 中編輯 OTP" h2="用於使用 PHP 代碼編輯 OTP 的高速跨平台 PHP 庫" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 編輯 OTP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/) 是一個功能強大的 PHP 庫，可快速輕鬆地編輯演示文稿。它為用戶提供了廣泛的功能，可幫助他們立即創建具有專業外觀的幻燈片。使用 Aspose，用戶可以編輯文本、添加圖像、動畫和過渡到他們的演示文稿，以及應用各種格式選項，如字體類型和顏色選擇。此外，該庫還支持 PowerPoint (PPT) 文件和 OpenOffice Presentation (ODP) 格式，這使得跨不同平台共享演示文稿比以往任何時候都更容易，而不會出現任何兼容性問題。通過在創建或編輯您的下一個演示文稿時利用 Aspose 庫的強大功能，您將確保您的幻燈片每次看起來都很棒！
您可以通過向其中添加新的文本行來編輯 OTP 文件。 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 PHP 中編輯 OTP" %}}
使用 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/)，您可以向 OTP 文檔添加一行新文本，只需幾行代碼。

{{% blocks/products/pf/agp/code-block title="用於編輯 OTP 的 PHP 代碼" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.otp", SaveFormat::Otp);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何在 PHP 中編輯 OTP" >}}

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
加載您要編輯的 OTP 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改的文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="編輯其他文件" subTitle="您還可以編輯其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}