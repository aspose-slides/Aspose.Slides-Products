---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 PHP 中將 SVG 合併為 PNG
url: /zh-hant/php-java/merger/svg-to-png/
keywords: 將 SVG 合併到 PNG、將 SVG 合併到 PNG、將 SVG 合併到 PNG、將 SVG 合併到 PNG、PHP API、PHP 庫
description: 在 PHP 中將 SVG 合併為 PNG。使用 PHP 庫 API 合併 SVG 和 PNG 文件
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 PHP 中將 SVG 合併為 PNG" h2="用於使用 PHP 代碼將 SVG 合併為 PNG 圖像的高速跨平台 PHP 庫" related="JPG,PNG,HTML,IMAGE,PDF,BMP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中將 SVG 合併為 PNG" variant="code" %}}

使用 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/)，只需幾行代碼即可快速將 SVG 合併為 PNG 文件

{{< blocks/products/pf/slides-design-update-10-2026/code title="將 SVG 合併為 PNG 的 PHP 代碼" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $svgImage1 = new SvgImage('image1.svg');
    $image1 = $pres->getImages()->addImage($svgImage1);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 0, 0, 360, 540, $image1);
    
    $svgImage2 = new SvgImage('image2.svg');
    $image2 = $pres->getImages()->addImage($svgImage2);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 360, 0, 360, 540, $image2);
    

    $img = $pres->getSlides()->get_Item(0)->getThumbnail(2, 2);
    $imageio = new Java("javax.imageio.ImageIO");
    $javafile = new Java("java.io.File", "merged-image.png");
    $imageio->write($img, "PNG", $javafile);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 將 SVG 合併為 PNG" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh-hant/php-java/) 是一個功能強大的 PHP 庫，用於合併和操作演示文稿、圖像和其他文件。當您將 SVG 合併到 PNG 時，您實際上是在組合 SVG 圖像以獲得 PNG 圖片。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 PHP 中將 SVG 合併為 PNG" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}通過 Java 安裝 **Aspose.Slides for PHP**。請參閱 [**安裝**](https://docs.aspose.com/slides/php-java/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加庫作為項目中的引用。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}創建一個 Presentation 類的實例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加載要合併在一起的 SVG 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存生成的 PNG 圖像。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="以 Aspose.Slides 建置" title="線上將 SVG 合併為 PNG" description="免費的 Aspose.Slides Merger 應用程式以 [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/zh-hant/php-java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 SVG 檔案。" button="開啟 Aspose.Slides Merger" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何合併檔案。
- 上傳多個 SVG 檔案並將它們合併為一個 PNG 檔案。
- 將合併結果下載為一個檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="合併其他文件" subTitle="您還可以合併其他格式的文件以獲得單個文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
