---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 PHP 中將 PPSX 轉換為 PPTX
weight: 2060
url: /zh-hant/php-java/conversion/ppsx-to-pptx/ 
keywords: "Convert, PowerPoint, PPSX, PPTX, Presentation, PHP"
description: PPSX 到 PPTX PHP 轉換的示例代碼。使用 PowerPoint PHP API 將 PPSX 文件批量轉換為 PPTX 文件。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 PHP 中將 PPSX 轉換為 PPTX" h2="用於將 PPSX 轉換為 PPTX 的強大 PowerPoint PHP 庫"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中將 PPSX 轉換為 PPTX" %}}

需要以編程方式將 PPSX 文件轉換為 PPTX？使用 [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/zh-hant/php-java/) 任何開發人員只需幾行 PHP 代碼即可將 PPSX 轉換為 PPTX 格式.

作為一個現代的演示處理 API，Aspose.Slides for PHP 從 PPSX 快速創建 PPTX。直接在您的 [瀏覽器](https://products.aspose.app/slides/conversion) 中測試 PPSX 到 PPTX 轉換的質量。 Aspose PowerPoint PPTX 庫允許您將 PPSX 文件轉換為許多流行的格式。

您可以使用以下命令從 [Composer](https://packagist.org/packages/aspose/slides) 安裝庫：

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="控制台/終端" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中將 PPSX 保存為 PPTX" %}}

使用免費應用查看 PPSX 到 PPTX 轉換過程的演示。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代碼顯示 PPSX 到 PPTX PHP 轉換" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
    $pres->save("output.pptx", SaveFormat::Pptx);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 PHP 中將 PPSX 轉換為 PPTX" intro="這些是使用 PHP 將 PPSX 文件轉換為 PPTX 的步驟。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 類的實例加載 PPSX 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定輸出文件路徑和 SaveFormat.PPTX 作為參數時調用 `save` 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX 文件將保存在指定路徑{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="系統要求" intro="在運行 PHP 轉換示例源代碼之前，請確保您具有以下先決條件。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 PHP 7，將 PHP 的路徑添加到系統 `PATH` 變量中，並在 `php.ini` 文件中將 `allow_url_include` 設置為 `On`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 JRE 8. 將 `JAVA_HOME` 環境變量設置為安裝的 JRE 位置的路徑。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 Apache Tomcat 8.0（參見 [更多](https://docs.aspose.com/slides/php-java/installation/)）。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPSX to PPTX"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 PPSX 轉換為許多其他文件格式。請參閱下面的其他支持的轉換" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="位圖圖像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="圖形交換格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="超文本標記語言" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="JPEG圖像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument 標準格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="便攜式文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="便攜式網絡圖形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="微軟 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="啟用宏的幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="微軟PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="啟用宏的演示文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="可縮放矢量圖形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="標記圖像格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
