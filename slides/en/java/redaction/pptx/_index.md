---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact PPTX Presentation Files using Java
url: /java/redaction/pptx/
keywords: Redact PPTX, find and replace text in PPTX, update PPTX Presentation
description: Find and replace text in PPTX presentations in Java using Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redact PPTX using Java" h2="Build Java applications that find and replace text in presentation files using server-side APIs." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redact a PPTX Presentation via Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can find and replace text in PPTX presentations. Use the `SlideUtil.findAndReplaceText` method to search the presentation and replace matching text with a new value.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Redact a PPTX Presentation using Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Redact PPTX via Java" intro="Follow these steps to redact a PPTX presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTX file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `SlideUtil.findAndReplaceText` method to find and replace text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the updated presentation with `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Redaction Formats" subTitle="Using Java, you can also redact the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
