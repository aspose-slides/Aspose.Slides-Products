---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Unlock ODP Presentation Files using .NET
url: /net/unlock/odp/
keywords: Remove ODP Write Protection, Decrypt ODP, Unlock ODP Presentation, Unprotect ODP
description: C# source code to remove password protection from ODP presentations.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Unlock ODP Files using C#" h2="Build .NET apps that remove encryption and write protection from presentations with server-side APIs." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remove Protection from an ODP Presentation using C#" variant="code" %}}

With [Aspose.Slides for .NET](/slides/net/), you can remove encryption or write protection from an ODP presentation. To remove encryption, load the presentation with the correct password and call `ProtectionManager.RemoveEncryption`. To remove write protection, call `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Remove Encryption from an ODP Presentation using C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Remove Write Protection from an ODP Presentation using C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Remove Protection from an ODP Presentation using C#" intro="Follow these steps to remove protection from an ODP presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the ODP file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}For an encrypted file, provide the password through `LoadOptions.Password` before loading it.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `ProtectionManager.RemoveEncryption` or `ProtectionManager.RemoveWriteProtection`, depending on the applied protection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the unlocked presentation with `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Unlocking Formats" subTitle="Using C#, you can also remove protection from the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
