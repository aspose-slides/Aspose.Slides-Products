---
title: 使用 C++ 保护 ODP 演示文件
url: /zh/cpp/protect/odp/
keywords: 写保护 ODP，加密 ODP，锁定 ODP 演示文稿，保护 ODP
description: C++ 源代码保护 ODP 演示。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 C++ 锁定或密码保护 ODP" h2="使用服务器端 API 构建您自己的 C++ 应用程序以保护演示文稿文件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 保护 ODP 演示文稿" %}}
使用 Aspose.Slides for C++，您可以通过设置密码来保护您的 ODP 演示文稿不被打开或修改。然后，要打开或修改锁定的演示文稿，用户必须提供密码。
{{% blocks/products/pf/agp/code-block title="使用 C++ 加密 ODP 演示文稿" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="使用 C++ 为 ODP 演示文稿设置写保护" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通过 C++ 密码保护 ODP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是保护 ODP 文件的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 实例加载 ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 ProtectionManager 类保护演示文稿
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 ODP 格式保存结果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的保护格式" subTitle="使用C++，您还可以保护以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}