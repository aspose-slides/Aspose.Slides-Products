---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protect PPTX Presentation Files using Java
url: /java/protect/pptx/
keywords: Write Protection PPTX, Encrypt a PPTX, Lock PPTX Presentation, Protect PPTX
description: Protect PPTX presentations in Java. Use Aspose.Slides for Java to encrypt presentation files and set write protection.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lock or Password Protect PPTX using Java" h2="Build Java applications that protect presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Protecting a PPTX Presentation via Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can protect a PPTX presentation from opening or modification by setting a password. Use the `ProtectionManager` object from the `Presentation` class to call methods such as `encrypt` and `setWriteProtection`.
{{% blocks/products/pf/agp/code-block title="Encrypt a PPTX Presentation using Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Set Write Protection for a PPTX Presentation using Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Password Protect PPTX via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to protect PPTX files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the `PPTX` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `encrypt` method or the `setWriteProtection` method from the `ProtectionManager` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the protected presentation in PPTX format.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protect Formats" subTitle="Using Java, you can also protect the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
