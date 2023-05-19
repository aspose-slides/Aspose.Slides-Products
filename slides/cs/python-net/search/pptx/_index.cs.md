---
title: Vyhledejte text v prezentačních souborech PPTX pomocí Python
url: /cs/python-net/search/pptx/
keywords: hledat slova ve PPTX, hledat a nahrazovat text ve PPTX, hledat text PPTX Prezentace
description: Zdrojový kód Python pro vyhledávání textu v prezentaci PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vyhledat text PPTX pomocí Python" h2="Vytvořte si vlastní aplikace pro Python pro vyhledávání a nahrazování textu v prezentačních souborech pomocí rozhraní API na straně serveru. Naučte se, jak najít všechny vstupy určitého slova nebo fráze v prezentačních dokumentech. Vyhledávejte text podle přesné shody dat a shody regulárních výrazů." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Vyhledat a nahradit text PPTX Prezentace prostřednictvím Python" %}}
Základní vyhledávání dokumentů a nahrazování textu v obsahu, komentářích, poznámkách ke snímkům nebo metadatech pomocí rozhraní API Aspose.Slides for Python via .NET lze provést pomocí několika řádků kódu. Pro vyhledávání textu v prezentaci použijte regulární výrazy a velká a malá písmena. Hledejte text v názvech, obsahu, zápatí nebo záhlaví.
{{% blocks/products/pf/agp/code-block title="Vyhledat text prezentace PPTX pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak hledat text ve PPTX prostřednictvím Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k vyhledávání textových souborů PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte PPTX s instancí Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
K vyhledání a nahrazení textu použijte metodu [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Hledejte živé ukázky" sectionDescription="Vyhledejte a nahraďte text v obsahu, komentářích nebo metadatech v dokumentech PPTX právě teď." >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty vyhledávání" subTitle="Pomocí Python můžete také vyhledávat text v následujících formátech:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}