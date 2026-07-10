---
title: Unlock PPTX Presentation Files using Java
url: /java/unlock/pptx/
keywords: Remove Write Protection PPTX, Decrypt PPTX, Unlock PPTX Presentation, Unprotect PPTX
description: Remove passwords and write protection from PPTX presentations in Java using Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Unlock PPTX using Java" h2="Build Java applications that remove passwords and write protection from presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Removing Protection from PPTX Presentation via Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can remove encryption or write protection from a PPTX presentation. Use `LoadOptions.setPassword` to open an encrypted presentation and the `ProtectionManager` methods `removeEncryption` and `removeWriteProtection` to remove protection settings.
{{% blocks/products/pf/agp/code-block title="Disable Password Protection from PPTX using Java" offSpacer="true" %}}

```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Remove Write Protection from PPTX Presentation using Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Remove Password From PPTX via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to remove protection from PPTX files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `PPTX` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use `LoadOptions.setPassword` when the presentation is encrypted.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `removeEncryption` or `removeWriteProtection` from the `ProtectionManager` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the unlocked presentation in PPTX format.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Formats" subTitle="Using Java, you can also remove protection from the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
