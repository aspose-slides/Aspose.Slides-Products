---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C# 为 PPT 演示文稿添加水印
url: /zh/net/watermark/ppt/
description: 使用 Aspose.Slides for .NET 在 C# 中为 PPT 演示文稿添加文本和图片水印。
keywords: 为 PPT 添加水印, 为 PPT 添加文本水印, 为 PPT 添加图片水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 为 PPT 演示文稿添加水印" h2="构建在演示文稿文件中插入文本或图片水印的 .NET 应用程序。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 C# 为 PPT 演示文稿添加水印" variant="code" %}}

借助 [Aspose.Slides for .NET](/slides/zh/net/)，可以为 PPT 演示文稿添加文本和图片水印。将水印形状添加到母版幻灯片，水印就会显示在使用该母版的幻灯片上。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 为 PPT 添加文本水印" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 为 PPT 演示文稿添加图片水印" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 为 PPT 添加水印" intro="按照以下步骤为 PPT 文件添加文本或图片水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 `PPT` 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}从 `Presentation.Masters` 集合中选择母版幻灯片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `AddAutoShape` 方法添加水印形状。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `AddTextFrame` 方法添加水印文本，或使用 `AddImage` 添加图片水印。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Ppt` 保存带水印的文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="基于 Aspose.Slides 构建" title="在线为 PPT 文件添加水印" description="免费的 Aspose.Slides Watermark 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Watermark" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何添加水印。
- 为 PPT 文件添加文本或图片水印。
- 下载带水印的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持水印的格式" subTitle="使用 C#，还可以为以下格式添加水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
