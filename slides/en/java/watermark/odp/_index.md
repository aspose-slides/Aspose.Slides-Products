---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Add Watermark to ODP Presentation Files using Java
url: /java/watermark/odp/
keywords: Add Watermark ODP, Add Text Watermark ODP, Add Image Watermark ODP
description: Add text and image watermarks to ODP presentations in Java using Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Add Watermark to ODP Presentation using Java" h2="Build Java applications that insert text or image watermarks into presentation files using server-side APIs." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Add Watermark to ODP Presentation via Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can add text and image watermarks to ODP presentations. Add a watermark shape to a master slide so the watermark appears on slides that use that master.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Add Text Watermark to ODP using Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Add Image Watermark to ODP Presentation using Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Add Watermark to ODP via Java" intro="Follow these steps to add a text or image watermark to ODP files." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the `ODP` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Select a master slide through the `getMasters` method.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `addAutoShape` method to add a watermark shape.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `addTextFrame` method to add watermark text or use `addImage` for an image watermark.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the watermarked presentation in ODP format.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Watermark Formats" subTitle="Using Java, you can also add watermarks to the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
