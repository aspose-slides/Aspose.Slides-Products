---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Remove ODP Annotations using Java
weight: 1790
url: /java/annotation/odp/
description: Remove comments and comment authors from ODP presentations in Java with Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Remove Comments and Comment Authors from ODP in Java" h2="Use Aspose.Slides for Java to remove comments and comment authors from presentation files." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remove Comments from ODP via Java" variant="code" %}}

Aspose.Slides for Java lets you remove comments and comment authors from ODP presentations. Load a file with the `Presentation` class, iterate through `ICommentAuthor` objects from `getCommentAuthors`, clear their comments, and save the updated presentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Delete Annotations from ODP - Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Remove Comments from ODP via Java" intro="Follow these steps to remove comments and comment authors from an ODP presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install Aspose.Slides for Java. See [Installation](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the ODP file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the `ICommentAuthor` objects from `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Clear each author's comments with `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Clear the comment author collection and save the updated ODP file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Annotation Formats" subTitle="Using Java, you can also remove annotations from other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
