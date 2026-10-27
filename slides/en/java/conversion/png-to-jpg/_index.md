---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to JPG in Java
url: /java/conversion/png-to-jpg/
keywords: PNG to JPG, Convert PNG to JPG, Java API, Java Library, PNG, JPG
description: Convert PNG to JPG in Java. Use Aspose.Slides for Java to add a PNG file to a slide and render it as a JPG image.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to JPG in Java" h2="Convert PNG files to JPG images using Aspose.Slides for Java without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to JPG using Java" variant="code" %}}

To convert `PNG` to `JPG`, add the source file to a `Presentation` and render the slide.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for converting PNG into JPG" >}}
```java
Presentation presentation = new Presentation();
try {
    ISlide slide = presentation.getSlides().get_Item(0);

    byte[] imageData = Files.readAllBytes(Paths.get("image.png"));
    IPPImage presentationImage = presentation.getImages().addImage(imageData);
    slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, presentationImage);

    IImage slideImage = slide.getImage(1f, 1f);
    try {
        slideImage.save("image.jpg", ImageFormat.Jpeg);
    } finally {
        slideImage.dispose();
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to JPG in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) is a presentation processing API that can place a `PNG` file on a slide and render the slide as a `JPG` image.

You can load a `PNG` file as an `IPPImage`, add it to a picture frame, render the slide as an `IImage`, and save the result with `ImageFormat.Jpeg`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PNG to JPG using Aspose.Slides for Java API" intro="These are the steps to convert PNG to JPG in Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Java**](/slides/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference (import the library) to your Java project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `PNG` file as an `IPPImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render the slide as an `IImage` and save it with `ImageFormat.Jpeg`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG To Other Supported Formats" subTitle="You can also convert PNG files and save them to other file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
