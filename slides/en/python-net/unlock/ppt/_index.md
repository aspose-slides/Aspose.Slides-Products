---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Unlock PPT Presentation Files using Python
url: /python-net/unlock/ppt/
keywords: Remove Write Protection PPT, Decrypt PPT, Unlock PPT Presentation, Unprotect PPT
description: Use Python code to remove encryption and write protection from PPT presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Unlock PPT using Python" h2="Build Python applications that remove passwords and write protection from PowerPoint presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Remove Encryption from a PPT Presentation with Python" %}}
Aspose.Slides for Python via .NET can remove encryption or write protection from a PPT presentation. After you load an encrypted file with the correct password, call `remove_encryption()` to save an unencrypted copy.
{{% blocks/products/pf/agp/code-block title="Remove Password Encryption from PPT with Python" offSpacer="true" %}}

```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Remove Write Protection from a PPT Presentation with Python" offSpacer="true" %}}

```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Remove a Password from PPT with Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to remove protection from PPT files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Set the password through `LoadOptions.password`, and load the PPT file into a `Presentation` instance.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `ProtectionManager.remove_encryption()` to remove encryption. For write-protected files, call `ProtectionManager.remove_write_protection()` instead.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save()` with `SaveFormat.PPT` to save the unlocked presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Formats" subTitle="You can also use Python to remove protection from the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
