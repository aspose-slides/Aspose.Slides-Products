---
title:  Protect PPTX Presentation Files using C++
url: /cpp/protect/pptx/
keywords: Write Protection PPTX, Encrypting a PPTX, Lock PPTX Presentation, Protect PPTX
description: C++ source code to protect PPTX Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lock or Password Protect PPTX using C++" h2="Build your own C++ apps to protect presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Protecting a PPTX Presentation via C++" %}}
Using Aspose.Slides for C++, you can protect your PPTX presentation from opening or modification by setting a password. Then, to open or modify the locked presentation, a user has to provide the password.
{{% blocks/products/pf/agp/code-block title="Encrypting a PPTX Presentation using C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Setting Write Protection to a PPTX Presentation using C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Password Protect PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to Protect PPTX files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPTX with an instance of Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Protect the presentation using ProtectionManager class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result in PPTX format
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protect Formats" subTitle="Using C++, You can also protect the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}