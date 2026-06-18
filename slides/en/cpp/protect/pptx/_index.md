---
title: Protect PPTX Presentations using C++
url: /cpp/protect/pptx/
keywords: Write Protection PPTX, Encrypt PPTX, Lock PPTX Presentation, Protect PPTX
description: Protect PPTX presentations in C++. Use Aspose.Slides for C++ to encrypt files and set write protection.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lock or Password Protect PPTX using C++" h2="Use Aspose.Slides for C++ to encrypt presentations and set write protection without Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Protecting a PPTX Presentation via C++" %}}
Aspose.Slides for C++ lets you protect PPTX presentations from opening or modification. Use the `ProtectionManager` object from the `Presentation` class to encrypt a file with `Encrypt` or restrict editing with `SetWriteProtection`.
{{% blocks/products/pf/agp/code-block title="Encrypting a PPTX Presentation using C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Setting Write Protection to a PPTX Presentation using C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Password Protect PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to protect PPTX files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PPTX file with the `Presentation` class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Protect the presentation with the `ProtectionManager` object.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use `Encrypt` for password protection or `SetWriteProtection` for write protection.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the protected file with `SaveFormat::Pptx`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protect Formats" subTitle="You can also protect the following formats with C++." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
