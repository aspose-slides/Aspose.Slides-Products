---
title: Merge SVG to PNG in Java
url: /java/merger/svg-to-png/
keywords: Merge SVG to PNG, SVG to PNG, Join SVG to PNG, Combine SVG to PNG, Java API, Java Library
description: Merge SVG to PNG in Java. Use Aspose.Slides for Java to combine SVG images and render the result as a PNG file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge SVG to PNG in Java" h2="Use Aspose.Slides for Java to merge SVG content in Java applications." >}}

{{% blocks/products/pf/feature-page-section h2="Merge SVG to PNG using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for creating, editing, converting, and merging presentation content. You can place `SVG` content into a `Presentation` and render the combined slide as a `PNG` image.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge SVG to PNG in Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can merge `SVG` content and create a `PNG` result with a few lines of Java code.

{{% blocks/products/pf/agp/code-block title="Java code for merging SVG to PNG" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    String firstSvgContent = new String(Files.readAllBytes(Paths.get("image1.svg")));
    ISvgImage firstSvgImage = new SvgImage(firstSvgContent);
    IPPImage firstPresentationImage = presentation.getImages().addImage(firstSvgImage);

    String secondSvgContent = new String(Files.readAllBytes(Paths.get("image2.svg")));
    ISvgImage secondSvgImage = new SvgImage(secondSvgContent);
    IPPImage secondPresentationImage = presentation.getImages().addImage(secondSvgImage);

    ISlide slide = presentation.getSlides().get_Item(0);
    slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, firstPresentationImage.getWidth(), firstPresentationImage.getHeight(), firstPresentationImage);
    slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, firstPresentationImage.getHeight(), secondPresentationImage.getWidth(), secondPresentationImage.getHeight(), secondPresentationImage);

    IImage mergedImage = slide.getImage(1f, 1f);
    try {
        mergedImage.save("merged.png", ImageFormat.Png);
    } finally {
        mergedImage.dispose();
    }
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge SVG to PNG in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create a `Presentation` instance.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the source `SVG` files with `Files.readAllBytes` and `Paths.get`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Render the slide with `getImage` and save it with `ImageFormat.Png`.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="svg-to-png" sectionTitle="Merge Files Online" sectionDescription="Merge presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/tiff-to-pdf/" name="TIFF TO PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
