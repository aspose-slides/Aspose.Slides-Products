---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 PHP 中将 SVG 转换为 PPTX
url: /zh/php-java/conversion/svg-to-pptx/
keywords: SVG 到 PPTX，将 SVG 转换为 PPTX，PHP API，PHP 库，SVG，PPTX
description: 在 PHP 中将 SVG 转换为 PPTX。使用 PowerPoint PHP API 将 SVG 文件转换为 PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 PHP 中将 SVG 转换为 PPTX" h2="强大的 PowerPoint PHP 库有助于开发应用程序，无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件即可创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 PHP 将 SVG 转换为 PPTX" variant="code" %}}

要将 SVG 转换为 PPTX，您需要从 SVG 文件创建演示文稿并将其另存为 PPTX。

{{< blocks/products/pf/slides-design-update-10-2026/code title="将 SVG 转换为 PPTX 的 PHP 代码" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.svg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $svgImage = new SvgImage($contents);
    $image = $pres->getImages()->addImage($svgImage);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 PHP 中将 SVG 转换为 PPTX" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh/php-java/) 是一个强大的 PHP 库，用于创建和操作演示文稿文件。此外，它提供了将 SVG 转换为 PPTX 的灵活方法。使用**Aspose.Slides for PHP via Java**，任何开发人员或应用程序只需几行 PHP 代码即可将 SVG 转换为 PPTX 文件。

作为现代文档处理 API，Aspose.Slides for PHP 可快速将 SVG 文件导出为 PPTX 文件格式。 Aspose PowerPoint 库允许您将 SVG 转换为 PPTX 和许多其他文件格式

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Aspose.Slides for PHP API 将 SVG 转换为 PPTX" intro="这些是在 PHP 中将 SVG 转换为 PPTX 的步骤。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/zh/php-java/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库引用（导入库）添加到您的 PHP 项目。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在 PHP 中打开源 SVG 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将结果保存为 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="基于 Aspose.Slides 构建" title="在线将 SVG 转换为 PPTX" description="免费的 Aspose.Slides Conversion 应用基于 [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/zh/php-java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 SVG 文件。" button="打开 Aspose.Slides Conversion" note="[所有免费应用](https://products.aspose.app/slides/family)" upload="拖放或上传您的文件" saveAs="另存为" convert="转换" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何转换文件。
- 上传 SVG 文件并将其另存为 PPTX。
- 下载结果或转换更多文件。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="将 SVG 转换为其他支持的格式" subTitle="您还可以转换 SVG 并保存为其他文件格式。查看下面所有支持的格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
