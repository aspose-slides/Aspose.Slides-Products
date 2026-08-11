---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert SVG to PNG in Java
url: /java/conversion/svg-to-png/
keywords: SVG to PNG, Convert SVG to PNG, Java API, Java Library, SVG, PNG
description: Convert SVG to PNG in Java. Use Aspose.Slides for Java to add an SVG file to a slide and render it as a PNG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert SVG to PNG in Java" h2="Convert SVG files to PNG images using Aspose.Slides for Java without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert SVG to PNG in Java" %}}

[Aspose.Slides for Java](/slides/java/) is a presentation processing API that can place an `SVG` file on a slide and render the slide as a `PNG` image.

You can load an `SVG` file as an `ISvgImage`, add it to a picture frame, and save the rendered slide image with `ImageFormat.Png`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert SVG to PNG using Java" %}}
To convert `SVG` to `PNG`, add the source file to a `Presentation` and render the slide with `getImage`.

{{% blocks/products/pf/agp/code-block title="Java code for converting SVG into PNG" offSpacer="true" %}}

```java
Presentation presentation = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes(Paths.get("image.svg")));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage presentationImage = presentation.getImages().addImage(svgImage);

    ISlide slide = presentation.getSlides().get_Item(0);
    slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, presentationImage.getWidth(), presentationImage.getHeight(), presentationImage);

    IImage slideImage = slide.getImage(1f, 1f);
    try {
        slideImage.save("image.png", ImageFormat.Png);
    } finally {
        slideImage.dispose();
    }
} finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert SVG to PNG using Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert SVG to PNG in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for Java](/slides/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `SVG` file as an `ISvgImage`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide as a `PNG` image with `getImage` and `ImageFormat.Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="svg-to-png" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert SVG To Other Supported Formats" subTitle="You can also convert SVG files and save them to other file formats." >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
