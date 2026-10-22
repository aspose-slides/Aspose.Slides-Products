---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge HTML to Image in Java
url: /java/merger/html-to-image/
keywords: Merge HTML to image, HTML to image, Join HTML, Combine HTML, Image, Java API, Java Library
description: Merge HTML to image in Java. Use Aspose.Slides for Java to combine HTML files and render the merged slides as images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge HTML to Image in Java" h2="Use Aspose.Slides for Java to merge HTML files in Java applications." related="JPG,PNG,HTML,IMAGE,BMP,PDF,SVG" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge HTML to PNG in Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can merge HTML files and create a `PNG` result with a few lines of Java code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for merging HTML to PNG" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);

    FileInputStream firstHtmlStream = new FileInputStream("file1.html");
    try {
        presentation.getSlides().addFromHtml(firstHtmlStream);
    } finally {
        firstHtmlStream.close();
    }

    FileInputStream secondHtmlStream = new FileInputStream("file2.html");
    try {
        presentation.getSlides().addFromHtml(secondHtmlStream);
    } finally {
        secondHtmlStream.close();
    }

    for (ISlide slide : presentation.getSlides()) {
        IImage slideImage = slide.getImage(1f, 1f);
        try {
            slideImage.save("slide_" + slide.getSlideNumber() + ".png", ImageFormat.Png);
        } finally {
            slideImage.dispose();
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge HTML to PNG using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for creating, editing, converting, and merging presentation content. You can place `HTML` files into a `Presentation` and render the merged slides as `PNG` images.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to merge HTML files in Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source `HTML` files with `addFromHtml`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each slide with `getImage` and save it with `ImageFormat.Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension="html-to-image"
  title="Merge Files Online"
  description="Merge presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Merge other files" subTitle="You can also combine files in other formats to get a single file." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
