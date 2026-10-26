---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protect PPT Presentation Files using .NET
url: /net/protect/ppt/
keywords: PPT Write Protection, Encrypt PPT, Lock PPT Presentation, Protect PPT
description: C# source code to password-protect PPT presentations.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lock or Password-Protect PPT Files using C#" h2="Build .NET apps that encrypt presentations and restrict modifications with server-side APIs." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protect a PPT Presentation using C#" variant="code" %}}

With [Aspose.Slides for .NET](/slides/net/), you can encrypt a PPT presentation or restrict its modification with a password. Opening a presentation encrypted with `ProtectionManager.Encrypt` requires the password. Use `ProtectionManager.SetWriteProtection` to allow opening the presentation while restricting changes.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Encrypt a PPT Presentation using C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Set Write Protection for a PPT Presentation using C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Password-Protect a PPT Presentation using C#" intro="Follow these steps to password-protect a PPT presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPT file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Encrypt the presentation with `ProtectionManager.Encrypt` or restrict changes with `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the protected file with `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Protection Formats" subTitle="Using C#, you can also protect the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
