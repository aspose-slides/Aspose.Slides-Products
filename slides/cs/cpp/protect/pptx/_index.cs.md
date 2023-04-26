---
title: Chraňte soubory prezentací PPTX pomocí C++
url: /cs/cpp/protect/pptx/
keywords: Ochrana proti zápisu PPTX, šifrování PPTX, zámek PPTX prezentace, ochrana PPTX
description: Zdrojový kód C++ k ochraně prezentace PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Uzamknout nebo chránit heslem PPTX pomocí C++" h2="Vytvářejte si vlastní aplikace pro C++, abyste chránili prezentační soubory pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrana PPTX prezentace prostřednictvím C++" %}}
Pomocí Aspose.Slides for C++ můžete chránit svou prezentaci PPTX před otevřením nebo úpravou nastavením hesla. Poté, aby uživatel mohl otevřít nebo upravit zamčenou prezentaci, musí zadat heslo.
{{% blocks/products/pf/agp/code-block title="Šifrování prezentace ve formátu PPTX pomocí C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Nastavení ochrany proti zápisu na prezentaci ve formátu PPTX pomocí C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak chránit heslem PPTX prostřednictvím C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k ochraně souborů PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte PPTX s instancí Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chraňte prezentaci pomocí třídy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty ochrany" subTitle="Pomocí C++ můžete chránit také následující formáty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}