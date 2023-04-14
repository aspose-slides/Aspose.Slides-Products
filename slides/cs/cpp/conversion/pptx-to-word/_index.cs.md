---
title: Převést PPTX na Word v C++
url: /cs/cpp/conversion/pptx-to-word/
keywords: Převod PPTX do Wordu, PPTX do Wordu, PPTX do DOC, PowerPoint do Wordu, C++ API, C++ Library, CPP
description: Převést PPTX na Word v C++. K převodu PowerPointu do Wordu použijte API knihovny C++
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převést PPTX na Word v C++" h2="Výkonné multiplatformní C++ API pro převod PowerPointu do Wordu pomocí C++ kódu bez Microsoft PowerPoint nebo Office" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PowerPoint do Wordu pomocí Aspose.Slides a Aspose.Words" %}}

[**Aspose.Slides pro C++**](https://products.aspose.com/slides/cs/cpp/) a [**Aspose.Words pro C++**](https://products.aspose.com/ words/cpp/) jsou výkonné knihovny C++ používané k manipulaci a převodu prezentací PowerPoint, dokumentů Word a dalších souborů. Při převodu PowerPointu do Wordu v podstatě přesouváte obsah snímků prezentace na stránky v dokumentu Wordu.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Převeďte PowerPoint do Wordu v C++" %}}
PPTX můžete rychle převést na Word pomocí několika řádků kódu

{{% blocks/products/pf/agp/code-block title="C++ kód pro převod PowerPointu do Wordu" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak převést PPTX na Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides pro C++** a **Aspose.Words pro C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation a třídy Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte prezentaci PPTX, kterou chcete převést do aplikace Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvářejte obrázky a texty na základě obsahu snímků.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledný dokument aplikace Word.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Zdarma online konvertor" sectionDescription="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="PowerPoint můžete také převést na soubory v jiných formátech" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}