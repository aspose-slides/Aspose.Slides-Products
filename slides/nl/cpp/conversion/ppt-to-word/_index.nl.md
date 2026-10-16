---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PPT naar Word in C++
url: /nl/cpp/conversion/ppt-to-word/
keywords: Converteer PPT naar Word, PPT naar Word, PPT naar DOC, PowerPoint naar Word, C++ API, C++ Library, CPP
description: Converteer PPT naar Word in C++. Gebruik de C++-bibliotheek-API om PowerPoint naar Word te converteren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PPT naar Word in C++" h2="Krachtige cross-platform C++ API voor het converteren van PowerPoint naar Word met behulp van C++-code zonder Microsoft PowerPoint of Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PowerPoint naar Word in C++" variant="code" %}}

U kunt PPT snel naar Word converteren met slechts een paar regels code

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-code voor het converteren van PowerPoint naar Word" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PowerPoint naar Word met behulp van Aspose.Slides en Aspose.Words" %}}

[**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/) en [**Aspose.Words voor C++**](https://products.aspose.com/ words/cpp/) zijn krachtige C++-bibliotheken die worden gebruikt om PowerPoint-presentaties, Word-documenten en andere bestanden te manipuleren en te converteren. Wanneer u PowerPoint naar Word converteert, verplaatst u in wezen de inhoud van de dia's van een presentatie naar pagina's in een Word-document.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PPT naar Word te converteren" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer **Aspose.Slides voor C++** en **Aspose.Words voor C++**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een instantie van de klasse Presentation en de klasse Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad de PPT-presentatie die u naar Word wilt converteren.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Genereer afbeeldingen en teksten op basis van de inhoud van de dia's.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het resulterende Word-document op.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis online converter"
  description="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PowerPoint ook converteren naar bestanden in andere formaten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
