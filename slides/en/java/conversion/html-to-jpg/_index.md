---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert HTML to JPG in Java
url: /java/conversion/html-to-jpg/
keywords: HTML to JPG, Convert HTML to JPG, Java API, Java Library, HTML, JPG
description: Convert HTML to JPG in Java. Use Java library API to convert HTML files to JPGs.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert HTML to JPG in Java" h2="Convert HTML files to JPG images using Aspose.Slides for Java without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to JPG using Java" variant="code" %}}

To convert `HTML` to `JPG`, create a new `Presentation`, remove its default slide, import the source HTML with `addFromHtml`, and render the resulting slides.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for converting HTML into JPG" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    try (FileInputStream htmlStream = new FileInputStream("page.html")) {
        presentation.getSlides().addFromHtml(htmlStream);
    }

    for (int slideIndex = 0; slideIndex < presentation.getSlides().size(); slideIndex++) {
        ISlide slide = presentation.getSlides().get_Item(slideIndex);
        IImage slideImage = slide.getImage(1f, 1f);
        try {
            slideImage.save("slide_" + (slideIndex + 1) + ".jpg", ImageFormat.Jpeg);
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to JPG in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) is a presentation processing API that can import `HTML` content and render the resulting slides as `JPG` images.

You can import an `HTML` file into a new `Presentation` with `addFromHtml`, render each resulting `ISlide` as an `IImage`, and save the output with `ImageFormat.Jpeg`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert HTML to JPG using Aspose.Slides for Java API" intro="These are the steps to convert HTML to JPG in Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Java**](/slides/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference (import the library) to your Java project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `HTML` file into a `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each `ISlide` as an `IImage` and save it as a `JPG` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert HTML To Other Supported Formats" subTitle="You can also convert HTML and save it to other file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
