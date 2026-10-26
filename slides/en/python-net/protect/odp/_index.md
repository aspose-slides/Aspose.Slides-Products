---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protect ODP Presentation Files with Python
url: /python-net/protect/odp/
keywords: ODP write protection, encrypt ODP with Python, lock ODP presentation, protect ODP with Python
description: Encrypt ODP presentations or set write protection with Python.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Protect ODP Presentations with Python" h2="Build Python applications that encrypt presentations or set write protection with Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protect an ODP Presentation with Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) provides two distinct protection mechanisms. Call `ProtectionManager.encrypt` to encrypt an ODP presentation and require a password to open it. Alternatively, call `ProtectionManager.set_write_protection` to discourage modification without encrypting the file. A user can still open a write-protected presentation and save changes to a different file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Encrypt an ODP Presentation - Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Set Write Protection on an ODP Presentation - Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Protect ODP with Python" intro="Follow these steps to protect an ODP file." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the ODP file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `ProtectionManager.encrypt` to require a password for opening, or use `ProtectionManager.set_write_protection` to discourage changes.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the protected presentation as ODP with `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Protection Formats" subTitle="Use Python to protect other supported presentation formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
