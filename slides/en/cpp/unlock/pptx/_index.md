---
title: Unlock PPTX Presentations using C++
url: /cpp/unlock/pptx/
keywords: Remove Write Protection PPTX, Decrypt PPTX, Unlock PPTX Presentation, Unprotect PPTX
description: Unlock PPTX presentations in C++. Use Aspose.Slides for C++ to remove encryption and write protection from presentation files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Unlock PPTX using C++" h2="Use Aspose.Slides for C++ to remove encryption and write protection from presentation files without Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Removing Encryption from PPTX Presentation via C++" %}}
Aspose.Slides for C++ lets you remove encryption or write protection from PPTX presentations. Use `LoadOptions` to open an encrypted file, then use the `ProtectionManager` object from the `Presentation` class to call `RemoveEncryption` or `RemoveWriteProtection`.
{{% blocks/products/pf/agp/code-block title="Disabling Password Protection from PPTX using C++" offSpacer="true" %}}

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Removing Write Protection from PPTX Presentation using C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Remove Password From PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to remove protection from PPTX files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PPTX file with the `Presentation` class and `LoadOptions` when a password is required.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use the `ProtectionManager` object to remove protection.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Call `RemoveEncryption` for encrypted files or `RemoveWriteProtection` for write-protected files.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the unlocked file with `SaveFormat::Pptx`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Formats" subTitle="You can also remove protection from the following formats with C++." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
