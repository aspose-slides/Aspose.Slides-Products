---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 PHP 中将 FODP 转换为 POT
weight: 90
url: /zh/php-java/conversion/fodp-to-pot/ 
keywords: "Convert, PowerPoint, FODP, POT, Presentation, PHP"
description: FODP 到 POT PHP 转换的示例代码。使用 PowerPoint PHP API 将 FODP 文件批量转换为 POT 文件。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 PHP 中将 FODP 转换为 POT" h2="用于将 FODP 转换为 POT 的强大 PowerPoint PHP 库"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中将 FODP 转换为 POT" %}}

需要以编程方式将 FODP 文件转换为 POT？使用 [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/zh/php-java/) 任何开发人员只需几行 PHP 代码即可将 FODP 转换为 POT 格式.

作为一个现代的演示处理 API，Aspose.Slides for PHP 从 FODP 快速创建 POT。直接在您的 [浏览器](https://products.aspose.app/slides/conversion) 中测试 FODP 到 POT 转换的质量。 Aspose PowerPoint PPTX 库允许您将 FODP 文件转换为许多流行的格式。

您可以使用以下命令从 [Composer](https://packagist.org/packages/aspose/slides) 安装库：

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="控制台/终端" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中将 FODP 保存为 POT" %}}

使用免费应用查看 FODP 到 POT 转换过程的演示。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代码显示 FODP 到 POT PHP 转换" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    $pres->save("output.pot", SaveFormat::Pot);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 PHP 中将 FODP 转换为 POT" intro="这些是使用 PHP 将 FODP 文件转换为 POT 的步骤。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 类的实例加载 FODP 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定输出文件路径和 SaveFormat.POT 作为参数时调用 `save` 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FODP 文件将保存在指定路径{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="系统要求" intro="在运行 PHP 转换示例源代码之前，请确保您具有以下先决条件。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 PHP 7，将 PHP 的路径添加到系统 `PATH` 变量中，并在 `php.ini` 文件中将 `allow_url_include` 设置为 `On`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 JRE 8. 将 `JAVA_HOME` 环境变量设置为安装的 JRE 位置的路径。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 Apache Tomcat 8.0（参见 [更多](https://docs.aspose.com/slides/php-java/installation/)）。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="基于 Aspose.Slides 构建" title="在线将 FODP 转换为 POT" description="免费的 Aspose.Slides Conversion 应用基于 [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/zh/php-java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 FODP 文件。" button="打开 Aspose.Slides Conversion" note="[所有免费应用](https://products.aspose.app/slides/family)" upload="拖放或上传您的文件" saveAs="另存为" convert="转换" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何转换文件。
- 上传 FODP 文件并将其另存为 POT。
- 下载结果或转换更多文件。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 FODP 转换为许多其他文件格式。请参阅下面的其他支持的转换" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="位图图像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="图形交换格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="超文本标记语言" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG图像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument 标准格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="便携式文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="便携式网络图形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="微软 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="幻灯片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="启用宏的幻灯片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="幻灯片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="微软PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="启用宏的演示文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="打开 XML 表示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="可缩放矢量图形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="标记图像格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
