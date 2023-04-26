---
title: 使用 C++ 保護 ODP 演示文件
url: /zh-hant/cpp/protect/odp/
keywords: 寫保護 ODP，加密 ODP，鎖定 ODP 演示文稿，保護 ODP
description: C++ 源代碼保護 ODP 演示。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 C++ 鎖定或密碼保護 ODP" h2="使用服務器端 API 構建您自己的 C++ 應用程序以保護演示文稿文件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 保護 ODP 演示文稿" %}}
使用 Aspose.Slides for C++，您可以通過設置密碼來保護您的 ODP 演示文稿不被打開或修改。然後，要打開或修改鎖定的演示文稿，用戶必須提供密碼。
{{% blocks/products/pf/agp/code-block title="使用 C++ 加密 ODP 演示文稿" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="使用 C++ 為 ODP 演示文稿設置寫保護" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 C++ 密碼保護 ODP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是保護 ODP 文件的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 實例加載 ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 ProtectionManager 類保護演示文稿
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 ODP 格式保存結果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的保護格式" subTitle="使用C++，您還可以保護以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}