---
title: Vyhledejte text v prezentačních souborech ODP pomocí .NET
url: /cs/net/search/odp/
keywords: hledat slova ve ODP, hledat a nahrazovat text ve ODP, hledat text ODP Prezentace
description: Zdrojový kód C# pro vyhledávání textu v prezentaci ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vyhledat text ODP pomocí C#" h2="Vytvořte si vlastní aplikace pro .NET pro vyhledávání a nahrazování textu v prezentačních souborech pomocí rozhraní API na straně serveru. Naučte se, jak najít všechny vstupy určitého slova nebo fráze v prezentačních dokumentech. Vyhledávejte text podle přesné shody dat a shody regulárních výrazů." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Vyhledat a nahradit text ODP Prezentace prostřednictvím C#" %}}
Základní vyhledávání dokumentů a nahrazování textu v obsahu, komentářích, poznámkách ke snímkům nebo metadatech pomocí rozhraní API Aspose.Slides for .NET lze provést pomocí několika řádků kódu. Pro vyhledávání textu v prezentaci použijte regulární výrazy a velká a malá písmena. Hledejte text v názvech, obsahu, zápatí nebo záhlaví.
{{% blocks/products/pf/agp/code-block title="Vyhledat text prezentace ODP pomocí C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak hledat text ve ODP prostřednictvím C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k vyhledávání textových souborů ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte ODP s instancí Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
K vyhledání a nahrazení textu použijte metodu [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Hledejte živé ukázky" sectionDescription="Vyhledejte a nahraďte text v obsahu, komentářích nebo metadatech v dokumentech ODP právě teď." >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty vyhledávání" subTitle="Pomocí C# můžete také vyhledávat text v následujících formátech:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}