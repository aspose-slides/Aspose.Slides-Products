---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protect PPTX Presentation Files with Python
url: /python-net/protect/pptx/
keywords: PPTX write protection, encrypt PPTX with Python, lock PPTX presentation, protect PPTX with Python
description: Encrypt PPTX presentations or set write protection with Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Protect PPTX Presentations with Python" h2="Build Python applications that encrypt presentations or set write protection with Aspose.Slides." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Protect a PPTX Presentation with Python" %}}
[**Aspose.Slides for Python via .NET**](/slides/python-net/) provides two distinct protection mechanisms. Call `ProtectionManager.encrypt` to encrypt a PPTX presentation and require a password to open it. Alternatively, call `ProtectionManager.set_write_protection` to discourage modification without encrypting the file. A user can still open a write-protected presentation and save changes to a different file.
{{% blocks/products/pf/agp/code-block title="Encrypt a PPTX Presentation - Python" offSpacer="true" %}}

```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Set Write Protection on a PPTX Presentation - Python" offSpacer="true" %}}

```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Protect PPTX with Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to protect a PPTX file." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the PPTX file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use `ProtectionManager.encrypt` to require a password for opening, or use `ProtectionManager.set_write_protection` to discourage changes.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the protected presentation as PPTX with `SaveFormat.PPTX`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protection Formats" subTitle="Use Python to protect other supported presentation formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
