---
title: Protect PPTX Presentation Files using .NET
url: /net/protect/pptx/
keywords: PPTX Write Protection, Encrypt PPTX, Lock PPTX Presentation, Protect PPTX
description: C# source code to password-protect PPTX presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lock or Password-Protect PPTX Files using C#" h2="Build .NET apps that encrypt presentations and restrict modifications with server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Protect a PPTX Presentation using C#" %}}
With [Aspose.Slides for .NET](/slides/net/), you can encrypt a PPTX presentation or restrict its modification with a password. Opening a presentation encrypted with `ProtectionManager.Encrypt` requires the password. Use `ProtectionManager.SetWriteProtection` to allow opening the presentation while restricting changes.
{{% blocks/products/pf/agp/code-block title="Encrypt a PPTX Presentation using C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Set Write Protection for a PPTX Presentation using C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Password-Protect a PPTX Presentation using C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to password-protect a PPTX presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPTX file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Encrypt the presentation with `ProtectionManager.Encrypt`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the protected file with `SaveFormat.Pptx`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protection Formats" subTitle="Using C#, you can also protect the following formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
