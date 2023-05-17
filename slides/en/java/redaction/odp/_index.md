---
title:  Redact ODP Presentation Files using Java
url: /java/redaction/odp/
keywords: Redact ODP, find and replace text in ODP, update ODP Presentation
description: Java source code to find and replace text in ODP Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact ODP using Java" h2="Build your own Java apps to find and replace text in presentation files using server-side APIs. Learn how to search and replace text in content, comments or metadata of ODP presentations" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact ODP Presentation via Java" %}}
A basic document search and replace text in contents, comments, slide notes or metadata with Aspose.Slides for Java APIs can be done with just few lines of code. Find and replace text in PowerPoint and OpenOffice. Edit text, comments, metadata in presentation via regexp data matching.
{{% blocks/products/pf/agp/code-block title="Redact ODP Presentation using Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to Redact ODP files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load ODP with an instance of Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) method to find and replace text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result in ODP format
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in ODP documents right now." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redact Formats" subTitle="Using Java, You can also redact the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}