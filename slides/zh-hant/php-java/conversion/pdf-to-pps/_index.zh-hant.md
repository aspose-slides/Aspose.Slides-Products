---
title: 在 PHP 中將 PDF 轉換為 PPS
weight: 750
url: /zh-hant/php-java/conversion/pdf-to-pps/ 
keywords: "Convert, PowerPoint, PDF, PPS, Presentation, PHP"
description: PDF 到 PPS PHP 轉換的示例代碼。使用 PowerPoint PHP API 將 PDF 文件批量轉換為 PPS 文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="在 PHP 中將 PDF 轉換為 PPS" h2="用於將 PDF 轉換為 PPS 的強大 PowerPoint PHP 庫" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="在 PHP 中將 PDF 轉換為 PPS" %}}

需要以編程方式將 PDF 文件轉換為 PPS？使用 [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/zh-hant/php-java/) 任何開發人員只需幾行 PHP 代碼即可將 PDF 轉換為 PPS 格式.

作為一個現代的演示處理 API，Aspose.Slides for PHP 從 PDF 快速創建 PPS。直接在您的 [瀏覽器](https://products.aspose.app/slides/conversion) 中測試 PDF 到 PPS 轉換的質量。 Aspose PowerPoint PPTX 庫允許您將 PDF 文件轉換為許多流行的格式。

您可以使用以下命令從 [Composer](https://packagist.org/packages/aspose/slides) 安裝庫：

{{% blocks/products/pf/agp/code-block title="控制台/終端" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="如何在 PHP 中將 PDF 轉換為 PPS" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是使用 PHP 將 PDF 文件轉換為 PPS 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 類的實例加載 PDF 文件
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在指定輸出文件路徑和 SaveFormat.PPS 作為參數時調用 `save` 方法
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PDF 文件將保存在指定路徑
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 PHP 轉換示例源代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

1. 安裝 PHP 7，將 PHP 的路徑添加到系統 `PATH` 變量中，並在 `php.ini` 文件中將 `allow_url_include` 設置為 `On`。
1. 安裝 JRE 8. 將 `JAVA_HOME` 環境變量設置為安裝的 JRE 位置的路徑。
1. 安裝 Apache Tomcat 8.0（參見 [更多](https://docs.aspose.com/slides/php-java/installation/)）。 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代碼顯示 PDF 到 PPS PHP 轉換" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
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
 
{{% blocks/products/pf/agp/content h2="在 PHP 中將 PDF 保存為 PPS" %}}
使用免費應用查看 PDF 到 PPS 轉換過程的演示。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PDF to PPS" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 PDF 轉換為許多其他文件格式。請參閱下面的其他支持的轉換" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="位圖圖像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-fodp/" name="PDF TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="圖形交換格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-html/" name="PDF TO HTML" description="超文本標記語言" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="JPEG圖像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="OpenDocument 標準格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="便攜式網絡圖形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-potm/" name="PDF TO POTM" description="微軟 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="啟用宏的幻燈片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="幻燈片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-ppt/" name="PDF TO PPT" description="微軟PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="啟用宏的演示文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="打開 XML 表示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="可縮放矢量圖形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="標記圖像格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="XML 紙張規格" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}