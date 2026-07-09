---
title: Redact PPTX Presentation Files using Java
url: /java/redaction/pptx/
keywords: Redact PPTX, find and replace text in PPTX, update PPTX Presentation
description: Find and replace text in PPTX presentations in Java using Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact PPTX using Java" h2="Build Java applications that find and replace text in presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact PPTX Presentation via Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can find and replace text in PPTX presentations. Use the `SlideUtil.findAndReplaceText` method to search the presentation and replace matching text with a new value.
{{% blocks/products/pf/agp/code-block title="Redact PPTX Presentation using Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact PPTX via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to redact PPTX files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `PPTX` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `SlideUtil.findAndReplaceText` method to find and replace text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the updated presentation in PPTX format.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction Live Demos" sectionDescription="Search and replace text in PPTX documents online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redact Formats" subTitle="Using Java, you can also redact the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
