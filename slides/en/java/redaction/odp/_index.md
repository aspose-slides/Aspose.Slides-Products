---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact ODP Presentation Files using Java
url: /java/redaction/odp/
keywords: Redact ODP, find and replace text in ODP, update ODP Presentation
description: Find and replace text in ODP presentations in Java using Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact ODP using Java" h2="Build Java applications that find and replace text in presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact ODP Presentation via Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can find and replace text in ODP presentations. Use the `SlideUtil.findAndReplaceText` method to search the presentation and replace matching text with a new value.
{{% blocks/products/pf/agp/code-block title="Redact ODP Presentation using Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to redact ODP files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `ODP` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `SlideUtil.findAndReplaceText` method to find and replace text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the updated presentation in ODP format.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redaction Live Demos" sectionDescription="Search and replace text in ODP documents online." >}}
{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redact Formats" subTitle="Using Java, you can also redact the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
