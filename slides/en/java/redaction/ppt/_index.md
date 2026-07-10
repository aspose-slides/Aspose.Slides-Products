---
title: Redact PPT Presentation Files using Java
url: /java/redaction/ppt/
keywords: Redact PPT, find and replace text in PPT, update PPT Presentation
description: Find and replace text in PPT presentations in Java using Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact PPT using Java" h2="Build Java applications that find and replace text in presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact PPT Presentation via Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can find and replace text in PPT presentations. Use the `SlideUtil.findAndReplaceText` method to search the presentation and replace matching text with a new value.
{{% blocks/products/pf/agp/code-block title="Redact PPT Presentation using Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact PPT via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to redact PPT files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `PPT` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `SlideUtil.findAndReplaceText` method to find and replace text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the updated presentation in PPT format.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Redaction Live Demos" sectionDescription="Search and replace text in PPT documents online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redact Formats" subTitle="Using Java, you can also redact the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
