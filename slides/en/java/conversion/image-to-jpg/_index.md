---
lastmod: 2026-09-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to JPG in Java
url: /java/conversion/image-to-jpg/
keywords: Image to JPG, Convert Image to JPG, Java API, Java Library, Image, JPG
description: Convert Image to JPG in Java. Use Aspose.Slides for Java to load an image file and save it as a JPG file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert Image to JPG in Java" h2="Convert image files to JPG using Aspose.Slides for Java without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to JPG using Java" variant="code" %}}

To convert an image to `JPG`, load the source image with `Images.fromFile` and save it in `JPG` format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for converting Image into JPG" >}}
```java
IImage image = Images.fromFile("image.png");
try {
    image.save("image.jpg", ImageFormat.Jpeg);
} finally {
    image.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to JPG in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) is a presentation processing API that can also load image files and save them as `JPG` files.

You can load an image as an `IImage` and save it with `ImageFormat.Jpeg`. The JPG keeps the width and height of the source image.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert Image to JPG using Aspose.Slides for Java API" intro="These are the steps to convert Image to JPG in Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Java**](/slides/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference (import the library) to your Java project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source image as an `IImage` with `Images.fromFile`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the image with `ImageFormat.Jpeg`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert Image To Other Supported Formats" subTitle="You can also convert images and save them to other file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
