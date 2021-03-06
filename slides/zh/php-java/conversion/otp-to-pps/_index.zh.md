---
title: 在 PHP 中将 OTP 转换为 PPS
weight: 540
url: /zh/php-java/conversion/otp-to-pps/ 
keywords: "Convert, PowerPoint, OTP, PPS, Presentation, PHP"
description: OTP 到 PPS PHP 转换的示例代码。使用 PowerPoint PHP API 将 OTP 文件批量转换为 PPS 文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="在 PHP 中将 OTP 转换为 PPS" h2="用于将 OTP 转换为 PPS 的强大 PowerPoint PHP 库" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="在 PHP 中将 OTP 转换为 PPS" %}}

需要以编程方式将 OTP 文件转换为 PPS？使用 [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/zh/php-java/) 任何开发人员只需几行 PHP 代码即可将 OTP 转换为 PPS 格式.

作为一个现代的演示处理 API，Aspose.Slides for PHP 从 OTP 快速创建 PPS。直接在您的 [浏览器](https://products.aspose.app/slides/conversion) 中测试 OTP 到 PPS 转换的质量。 Aspose PowerPoint PPTX 库允许您将 OTP 文件转换为许多流行的格式。

您可以使用以下命令从 [Composer](https://packagist.org/packages/aspose/slides) 安装库：

{{% blocks/products/pf/agp/code-block title="控制台/终端" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="如何在 PHP 中将 OTP 转换为 PPS" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是使用 PHP 将 OTP 文件转换为 PPS 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 类的实例加载 OTP 文件
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在指定输出文件路径和 SaveFormat.PPS 作为参数时调用 `save` 方法
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
OTP 文件将保存在指定路径
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 PHP 转换示例源代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

1. 安装 PHP 7，将 PHP 的路径添加到系统 `PATH` 变量中，并在 `php.ini` 文件中将 `allow_url_include` 设置为 `On`。
1. 安装 JRE 8. 将 `JAVA_HOME` 环境变量设置为安装的 JRE 位置的路径。
1. 安装 Apache Tomcat 8.0（参见 [更多](https://docs.aspose.com/slides/php-java/installation/)）。 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代码显示 OTP 到 PPS PHP 转换" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
    $pres->save("output.pps", SaveFormat::Pps);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="在 PHP 中将 OTP 保存为 PPS" %}}
使用免费应用查看 OTP 到 PPS 转换过程的演示。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert OTP to PPS" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 OTP 转换为许多其他文件格式。请参阅下面的其他支持的转换" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-bmp/" name="OTP TO BMP" description="位图图像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-fodp/" name="OTP TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="图形交换格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-html/" name="OTP TO HTML" description="超文本标记语言" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="JPEG图像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="便携式文件格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-png/" name="OTP TO PNG" description="便携式网络图形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="微软 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="启用宏的幻灯片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="幻灯片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="微软PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="启用宏的演示文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="打开 XML 表示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="可缩放矢量图形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="标记图像格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="XML 纸张规格" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}