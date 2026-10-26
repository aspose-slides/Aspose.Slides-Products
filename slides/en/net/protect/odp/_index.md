---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protect ODP Presentation Files using .NET
url: /net/protect/odp/
keywords: ODP Write Protection, Encrypt ODP, Lock ODP Presentation, Protect ODP
description: C# source code to password-protect ODP presentations.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lock or Password-Protect ODP Files using C#" h2="Build .NET apps that encrypt presentations and restrict modifications with server-side APIs." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protect an ODP Presentation using C#" variant="code" %}}

With [Aspose.Slides for .NET](/slides/net/), you can encrypt an ODP presentation or restrict its modification with a password. Opening a presentation encrypted with `ProtectionManager.Encrypt` requires the password. Use `ProtectionManager.SetWriteProtection` to allow opening the presentation while restricting changes.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Encrypt an ODP Presentation using C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Set Write Protection for an ODP Presentation using C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Password-Protect an ODP Presentation using C#" intro="Follow these steps to password-protect an ODP presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the ODP file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Encrypt the presentation with `ProtectionManager.Encrypt` or restrict changes with `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the protected file with `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Protection Formats" subTitle="Using C#, you can also protect the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
