---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit HTML in Java
url: /java/editor/html/
keywords: Edit HTML, HTML, Java API, Java Library
description: Edit HTML files in Java. Use Aspose.Slides for Java to modify HTML content and save the edited file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit HTML in Java" h2="Use Aspose.Slides for Java to edit HTML files in Java applications." related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML in Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can edit an `HTML` file by adding a text shape and saving the result with `SaveFormat.Html`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for editing HTML" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    FileInputStream htmlInputStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlInputStream);
    } finally {
        htmlInputStream.close();
    }

    ISlide slide = presentation.getSlides().get_Item(0);
    IAutoShape textBox = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    textBox.getTextFrame().setText("New text");

    presentation.save("page.html", SaveFormat.Html);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) is a Java API for working with presentation content. You can import an `HTML` file into a `Presentation`, add a text shape, and save the edited content as `HTML`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit HTML in Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance and import the source `HTML` content.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the slide you want to edit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a text shape with `addAutoShape` and `setText`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the edited `HTML` file with `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
