---
title: Proteger arquivos de apresentação ODP usando C++
url: /pt/cpp/protect/odp/
keywords: Proteção contra gravação ODP, criptografia de uma apresentação ODP, bloqueio ODP, proteção ODP
description: Código-fonte C++ para proteger a apresentação ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bloqueie ou proteja com senha ODP usando C++" h2="Crie seus próprios aplicativos C++ para proteger arquivos de apresentação usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Protegendo uma apresentação ODP via C++" %}}
Usando Aspose.Slides for C++, você pode proteger sua apresentação ODP contra abertura ou modificação definindo uma senha. Então, para abrir ou modificar a apresentação bloqueada, o usuário deve fornecer a senha.
{{% blocks/products/pf/agp/code-block title="Criptografando uma apresentação ODP usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Configurando proteção contra gravação para uma apresentação ODP usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como proteger com senha ODP via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para proteger arquivos ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar ODP com uma instância de Apresentação
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteja a apresentação usando a classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de proteção suportados" subTitle="Usando C++, você também pode proteger os seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}