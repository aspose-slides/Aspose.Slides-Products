---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 PHP 中将 PPSX 转换为 PPSM
weight: 2030
url: /zh/php-java/conversion/ppsx-to-ppsm/ 
keywords: "Convert, PowerPoint, PPSX, PPSM, Presentation, PHP"
description: PPSX 到 PPSM PHP 转换的示例代码。使用 PowerPoint PHP API 将 PPSX 文件批量转换为 PPSM 文件。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 PHP 中将 PPSX 转换为 PPSM" h2="用于将 PPSX 转换为 PPSM 的强大 PowerPoint PHP 库"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中将 PPSX 转换为 PPSM" %}}

需要以编程方式将 PPSX 文件转换为 PPSM？使用 [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/zh/php-java/) 任何开发人员只需几行 PHP 代码即可将 PPSX 转换为 PPSM 格式.

作为一个现代的演示处理 API，Aspose.Slides for PHP 从 PPSX 快速创建 PPSM。直接在您的 [浏览器](https://products.aspose.app/slides/conversion) 中测试 PPSX 到 PPSM 转换的质量。 Aspose PowerPoint PPTX 库允许您将 PPSX 文件转换为许多流行的格式。

您可以使用以下命令从 [Composer](https://packagist.org/packages/aspose/slides) 安装库：

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="控制台/终端" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中将 PPSX 保存为 PPSM" %}}

使用免费应用查看 PPSX 到 PPSM 转换过程的演示。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代码显示 PPSX 到 PPSM PHP 转换" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
    $pres->save("output.ppsm", SaveFormat::Ppsm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 PHP 中将 PPSX 转换为 PPSM" intro="这些是使用 PHP 将 PPSX 文件转换为 PPSM 的步骤。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 类的实例加载 PPSX 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定输出文件路径和 SaveFormat.PPSM 作为参数时调用 `save` 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX 文件将保存在指定路径{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="系统要求" intro="在运行 PHP 转换示例源代码之前，请确保您具有以下先决条件。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 PHP 7，将 PHP 的路径添加到系统 `PATH` 变量中，并在 `php.ini` 文件中将 `allow_url_include` 设置为 `On`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 JRE 8. 将 `JAVA_HOME` 环境变量设置为安装的 JRE 位置的路径。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 Apache Tomcat 8.0（参见 [更多](https://docs.aspose.com/slides/php-java/installation/)）。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPSX to PPSM"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 PPSX 转换为许多其他文件格式。请参阅下面的其他支持的转换" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="位图图像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="图形交换格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="超文本标记语言" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="JPEG图像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument 标准格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="便携式文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="便携式网络图形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="微软 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="幻灯片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="微软PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="启用宏的演示文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="打开 XML 表示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="可缩放矢量图形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="标记图像格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
