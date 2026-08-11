---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Unlock ODP Presentation Files using .NET
url: /net/unlock/odp/
keywords: Remove ODP Write Protection, Decrypt ODP, Unlock ODP Presentation, Unprotect ODP
description: C# source code to remove password protection from ODP presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Unlock ODP Files using C#" h2="Build .NET apps that remove encryption and write protection from presentations with server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Remove Protection from an ODP Presentation using C#" %}}
With [Aspose.Slides for .NET](/slides/net/), you can remove encryption or write protection from an ODP presentation. To remove encryption, load the presentation with the correct password and call `ProtectionManager.RemoveEncryption`. To remove write protection, call `ProtectionManager.RemoveWriteProtection`.
{{% blocks/products/pf/agp/code-block title="Remove Encryption from an ODP Presentation using C#" offSpacer="true" %}}

```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Remove Write Protection from an ODP Presentation using C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Remove Protection from an ODP Presentation using C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to remove protection from an ODP presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the ODP file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
For an encrypted file, provide the password through `LoadOptions.Password` before loading it.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `ProtectionManager.RemoveEncryption` or `ProtectionManager.RemoveWriteProtection`, depending on the applied protection.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the unlocked presentation with `SaveFormat.Odp`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Unlocking Formats" subTitle="Using C#, you can also remove protection from the following formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
