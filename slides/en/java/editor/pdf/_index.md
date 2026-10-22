---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit PDF in Java
url: /java/editor/pdf/
keywords: Edit PDF, PDF, Java API, Java Library
description: Edit PDF files in Java. Use Aspose.Slides for Java to modify PDF content and save the edited file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit PDF in Java" h2="Use Aspose.Slides for Java to edit PDF files in Java applications." related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF in Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can edit a `PDF` file by adding a text shape and saving the result with `SaveFormat.Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for editing PDF" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    presentation.getSlides().addFromPdf("document.pdf");

    ISlide slide = presentation.getSlides().get_Item(0);
    IAutoShape textBox = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    textBox.getTextFrame().setText("New text");

    presentation.save("document.pdf", SaveFormat.Pdf);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for working with presentation content. You can import a `PDF` file into a `Presentation`, add a text shape, and save the edited content as `PDF`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit PDF in Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance and import the source `PDF` content.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the slide you want to edit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a text shape with `addAutoShape` and `setText`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the edited file with `SaveFormat.Pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
