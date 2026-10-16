---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 PHP 中將 PPTX 轉換為 GIF
weight: 2550
url: /zh-hant/php-java/conversion/pptx-to-gif/ 
keywords: "Convert, PowerPoint, PPTX, GIF, Presentation, PHP"
description: PPTX 到 GIF PHP 轉換的示例代碼。使用 PowerPoint PHP API 將 PPTX 文件批量轉換為 GIF 文件。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 PHP 中將 PPTX 轉換為 GIF" h2="用於將 PPTX 轉換為 GIF 的強大 PowerPoint PHP 庫"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中將 PPTX 轉換為 GIF" %}}

需要以編程方式將 PPTX 文件轉換為 GIF？使用 [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/zh-hant/php-java/) 任何開發人員只需幾行 PHP 代碼即可將 PPTX 轉換為 GIF 格式.

作為一個現代的演示處理 API，Aspose.Slides for PHP 從 PPTX 快速創建 GIF。直接在您的 [瀏覽器](https://products.aspose.app/slides/conversion) 中測試 PPTX 到 GIF 轉換的質量。 Aspose PowerPoint PPTX 庫允許您將 PPTX 文件轉換為許多流行的格式。

您可以使用以下命令從 [Composer](https://packagist.org/packages/aspose/slides) 安裝庫：

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="控制台/終端" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中將 PPTX 保存為 GIF" %}}

使用免費應用查看 PPTX 到 GIF 轉換過程的演示。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代碼顯示 PPTX 到 GIF PHP 轉換" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $pres->save("output.gif", SaveFormat::Gif);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 PHP 中將 PPTX 轉換為 GIF" intro="這些是使用 PHP 將 PPTX 文件轉換為 GIF 的步驟。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 類的實例加載 PPTX 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定輸出文件路徑和 SaveFormat.GIF 作為參數時調用 `save` 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX 文件將保存在指定路徑{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="系統要求" intro="在運行 PHP 轉換示例源代碼之前，請確保您具有以下先決條件。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 PHP 7，將 PHP 的路徑添加到系統 `PATH` 變量中，並在 `php.ini` 文件中將 `allow_url_include` 設置為 `On`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 JRE 8. 將 `JAVA_HOME` 環境變量設置為安裝的 JRE 位置的路徑。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 Apache Tomcat 8.0（參見 [更多](https://docs.aspose.com/slides/php-java/installation/)）。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTX to GIF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 PPTX 轉換為許多其他文件格式。請參閱下面的其他支持的轉換" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="位圖圖像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="超文本標記語言" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="JPEG圖像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument 標準格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="便攜式文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="便攜式網絡圖形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="微軟 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="啟用宏的幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="微軟PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="啟用宏的演示文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="可縮放矢量圖形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="標記圖像格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
