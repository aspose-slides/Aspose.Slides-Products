---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge Image to BMP in Java
url: /java/merger/image-to-bmp/
keywords: Image to BMP, Merge image to BMP, Join image to BMP, Combine images, Image, BMP, Java API, Java Library
description: Merge images to BMP in Java. Use Aspose.Slides for Java to combine images on a slide and render the result as a BMP file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge Image to BMP in Java" h2="Use Aspose.Slides for Java to merge images in Java applications." related="JPG,PNG,HTML,IMAGE,PDF,SVG" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge image to BMP in Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can merge images and create a `BMP` result with a few lines of Java code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for merging image to BMP" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge image to BMP using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for creating, editing, converting, and merging presentation content. You can place images into a `Presentation` and render the combined slide as a `BMP` file.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to merge images in Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source images with `Files.readAllBytes` and `Paths.get`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render the slide with `getImage` and save it with `ImageFormat.Bmp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Merge other files" subTitle="You can also combine files in other formats to get a single file." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
