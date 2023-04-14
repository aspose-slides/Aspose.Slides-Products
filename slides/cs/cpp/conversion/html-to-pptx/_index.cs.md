---
title: Převést HTML na PPTX v C++
url: /cs/cpp/conversion/html-to-pptx/
keywords: Převod HTML na PPTX, HTML na PPTX, PowerPoint, HTML, PPTX, C++ API, C++ knihovna
description: Převést HTML na PPTX v C++. K převodu HTML do PowerPointu použijte API knihovny C++
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převést HTML na PPTX v C++" h2="Výkonné multiplatformní C++ API pro převod HTML do PPTX pomocí C++ kódu" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte HTML na PPTX pomocí Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/) je výkonná knihovna C++, která se používá k vytváření, převodu a manipulaci s prezentacemi PowerPoint, PDF, HTML dokumenty a dalšími soubory. Při převodu HTML na PPTX v podstatě přesouváte obsah dokumentu HTML na snímky v prezentaci PowerPoint.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Převést HTML na PPTX v C++" %}}
Pomocí [**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/) můžete převést dokument HTML na prezentaci v PowerPointu pomocí několika řádků kódu:

{{% blocks/products/pf/agp/code-block title="C++ kód pro převod HTML do PPTX" offSpacer="true" %}}
```cpp
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak převést HTML na PPTX v C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides pro C++**. Viz [**Instalace**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte knihovnu jako referenci do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte dokument HTML, který chcete převést na PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledný soubor jako prezentaci PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Zdarma online konvertor" sectionDescription="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované převody PowerPoint" subTitle="Můžete také převést soubory v jiných formátech do PowerPointu" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}