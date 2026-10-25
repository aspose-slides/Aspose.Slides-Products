---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Add Watermark to PPTX Presentations using C#
url: /net/watermark/pptx/
keywords: Add Watermark PPTX, Add Text Watermark PPTX, Add Image Watermark PPTX
description: Add text and image watermarks to PPTX presentations in C# using Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Add Watermark to PPTX Presentation using C#" h2="Build .NET applications that insert text or image watermarks into presentation files." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Add Watermark to PPTX Presentation via C#" variant="code" %}}

Using [Aspose.Slides for .NET](/slides/net/), you can add text and image watermarks to PPTX presentations. Add a watermark shape to a master slide so the watermark appears on slides that use that master.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Add Text Watermark to PPTX using C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Add Image Watermark to PPTX Presentation using C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Add Watermark to PPTX via C#" intro="Follow these steps to add a text or image watermark to PPTX files." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the `PPTX` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Select a master slide from the `Presentation.Masters` collection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `AddAutoShape` method to add a watermark shape.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `AddTextFrame` method to add watermark text or use `AddImage` for an image watermark.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the watermarked file with `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Watermark Formats" subTitle="Using C#, you can also add watermarks to the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
