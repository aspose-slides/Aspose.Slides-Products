---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to JPG in Java
url: /java/conversion/pdf-to-jpg/
keywords: PDF to JPG, Convert PDF to JPG, Java API, Java Library, PDF, JPG
description: Convert PDF to JPG in Java. Use Aspose.Slides for Java to render PDF files as JPG images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to JPG in Java" h2="Convert PDF files to JPG with Aspose.Slides for Java without Adobe Acrobat." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to JPG using Java" variant="code" %}}

To convert `PDF` to `JPG`, create a `Presentation`, import the source file with `ISlideCollection.addFromPdf`, and render the imported slides as images.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for converting PDF into JPG" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().addFromPdf("input.pdf");
    for (ISlide slide : presentation.getSlides()) {
        IImage slideImage = slide.getImage(1f, 1f);
        try {
            slideImage.save("slide_" + slide.getSlideNumber() + ".jpg", ImageFormat.Jpeg);
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to JPG in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) lets you import `PDF` files into a presentation and render slides as `JPG` images. With this Java API, you can convert `PDF` content without Adobe Acrobat.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to JPG using Aspose.Slides for Java API" intro="These are the steps to convert PDF to JPG in Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Java**](/slides/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference (import the library) to your Java project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source `PDF` file in Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save each slide as a `JPG` image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
