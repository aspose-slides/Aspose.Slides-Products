---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Unlock ODP Presentations with Python
url: /python-net/unlock/odp/
keywords: unlock ODP, remove password from ODP, remove ODP encryption, remove write protection from ODP
description: Remove encryption and write protection from ODP presentations with Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Unlock ODP Presentations with Python" h2="Build Python applications that remove opening passwords and write-protection settings from ODP presentations with Aspose.Slides." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Remove Encryption and Write Protection from ODP with Python" %}}
With [Aspose.Slides for Python via .NET](/slides/python-net/), you can remove encryption that requires a password to open an ODP presentation, or clear its write-protection setting. To open an encrypted file, provide the current password through `LoadOptions`.
{{% blocks/products/pf/agp/code-block title="Remove Encryption from an ODP Presentation - Python" offSpacer="true" %}}

```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Remove Write Protection from an ODP Presentation - Python" offSpacer="true" %}}

```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Remove Protection from ODP with Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to remove protection from an ODP presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
For an encrypted ODP file, set the current password in `LoadOptions`, and then open the file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `ProtectionManager.remove_encryption` to remove the opening password, or call `ProtectionManager.remove_write_protection` to clear write protection.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the resulting presentation with `SaveFormat.ODP`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Formats" subTitle="Use Python to remove protection from other supported presentation formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
