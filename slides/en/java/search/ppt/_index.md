---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Search Text in PPT Presentation Files using Java
url: /java/search/ppt/
keywords: search words in PPT, search text in PPT, search text PPT Presentation
description: Search text in PPT presentations in Java using Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Search Text in PPT using Java" h2="Build Java applications that search text in presentation files using server-side APIs." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Search Text in a PPT Presentation via Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can search text in PPT presentations. Use the `SlideUtil.getAllTextBoxes` method to collect text frames and then inspect `ITextFrame`, `IParagraph`, and `IPortion` objects.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Search Text in a PPT Presentation using Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Search Text in PPT via Java" intro="Follow these steps to search text in a PPT presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPT file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `SlideUtil.getAllTextBoxes` method to collect text frames from each slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Inspect `ITextFrame`, `IParagraph`, and `IPortion` objects to find matching text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Search Formats" subTitle="Using Java, you can also search text in the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
