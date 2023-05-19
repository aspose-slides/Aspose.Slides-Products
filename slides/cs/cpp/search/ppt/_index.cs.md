---
title: Vyhledejte text v prezentačních souborech PPT pomocí C++
url: /cs/cpp/search/ppt/
keywords: hledat slova ve PPT, hledat a nahrazovat text ve PPT, hledat text PPT Prezentace
description: Zdrojový kód C++ pro vyhledávání textu v prezentaci PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vyhledat text PPT pomocí C++" h2="Vytvořte si vlastní aplikace pro C++ pro vyhledávání a nahrazování textu v prezentačních souborech pomocí rozhraní API na straně serveru. Naučte se, jak najít všechny vstupy určitého slova nebo fráze v prezentačních dokumentech. Vyhledávejte text podle přesné shody dat a shody regulárních výrazů." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Vyhledat a nahradit text PPT Prezentace prostřednictvím C++" %}}
Základní vyhledávání dokumentů a nahrazování textu v obsahu, komentářích, poznámkách ke snímkům nebo metadatech pomocí rozhraní API Aspose.Slides for C++ lze provést pomocí několika řádků kódu. Pro vyhledávání textu v prezentaci použijte regulární výrazy a velká a malá písmena. Hledejte text v názvech, obsahu, zápatí nebo záhlaví.
{{% blocks/products/pf/agp/code-block title="Vyhledat text prezentace PPT pomocí C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.ppt", SaveFormat::Ppt);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak hledat text ve PPT prostřednictvím C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k vyhledávání textových souborů PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte PPT s instancí Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
K vyhledání a nahrazení textu použijte metodu [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Hledejte živé ukázky" sectionDescription="Vyhledejte a nahraďte text v obsahu, komentářích nebo metadatech v dokumentech PPT právě teď." >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty vyhledávání" subTitle="Pomocí C++ můžete také vyhledávat text v následujících formátech:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}