---
title:  Protect PPTX Presentation Files using .NET
url: /net/protect/pptx/
keywords: Write Protection PPTX, Encrypting a PPTX, Lock PPTX Presentation, Protect PPTX
description: C# source code to protect PPTX Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lock or Password Protect PPTX using C#" h2="Build your own .NET apps to protect presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Protecting a PPTX Presentation via C#" %}}
Using Aspose.Slides for .NET, you can protect your PPTX presentation from opening or modification by setting a password. Then, to open or modify the locked presentation, a user has to provide the password.
{{% blocks/products/pf/agp/code-block title="Encrypting a PPTX Presentation using C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Setting Write Protection to a PPTX Presentation using C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Password Protect PPTX via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to Protect PPTX files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPTX with an instance of Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Protect the presentation using ProtectionManager class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result in PPTX format
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protect Formats" subTitle="Using C#, You can also protect the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}