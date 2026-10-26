---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Unlock PPTX Presentations with Python
url: /python-net/unlock/pptx/
keywords: unlock PPTX, remove password from PPTX, remove PPTX encryption, remove write protection from PPTX
description: Remove encryption and write protection from PPTX presentations with Python.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Unlock PPTX Presentations with Python" h2="Build Python applications that remove opening passwords and write-protection settings from PPTX presentations with Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remove Encryption and Write Protection from PPTX with Python" variant="code" %}}

With [Aspose.Slides for Python via .NET](/slides/python-net/), you can remove encryption that requires a password to open a PPTX presentation, or clear its write-protection setting. To open an encrypted file, provide the current password through `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Remove Encryption from a PPTX Presentation - Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Remove Write Protection from a PPTX Presentation - Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Remove Protection from PPTX with Python" intro="Follow these steps to remove protection from a PPTX presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}For an encrypted PPTX file, set the current password in `LoadOptions`, and then open the file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `ProtectionManager.remove_encryption` to remove the opening password, or call `ProtectionManager.remove_write_protection` to clear write protection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the resulting presentation with `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Unlocking Formats" subTitle="Use Python to remove protection from other supported presentation formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
