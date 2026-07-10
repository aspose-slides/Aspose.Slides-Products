---
title: Merge Image to BMP in Java
url: /java/merger/image-to-bmp/
keywords: Image to BMP, Merge image to BMP, Join image to BMP, Combine images, Image, BMP, Java API, Java Library
description: Merge images to BMP in Java. Use Aspose.Slides for Java to combine images on a slide and render the result as a BMP file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge Image to BMP in Java" h2="Use Aspose.Slides for Java to merge images in Java applications." >}}

{{% blocks/products/pf/feature-page-section h2="Merge image to BMP using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for creating, editing, converting, and merging presentation content. You can place images into a `Presentation` and render the combined slide as a `BMP` file.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge image to BMP in Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can merge images and create a `BMP` result with a few lines of Java code.

{{% blocks/products/pf/agp/code-block title="Java code for merging image to BMP" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    ISlide slide = presentation.getSlides().get_Item(0);

    byte[] firstImageData = Files.readAllBytes(Paths.get("image1.png"));
    IPPImage firstImage = presentation.getImages().addImage(firstImageData);
    slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, firstImage);

    byte[] secondImageData = Files.readAllBytes(Paths.get("image2.png"));
    IPPImage secondImage = presentation.getImages().addImage(secondImageData);
    slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, secondImage);

    IImage mergedImage = slide.getImage(1f, 1f);
    try {
        mergedImage.save("merged.bmp", ImageFormat.Bmp);
    } finally {
        mergedImage.dispose();
    }
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge images in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` instance.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source images with `Files.readAllBytes` and `Paths.get`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `getImage` and save it with `ImageFormat.Bmp`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="image-to-bmp" sectionTitle="Merge Files Online" sectionDescription="Merge presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/merger/svg-to-png/" name="SVG TO PNG" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
