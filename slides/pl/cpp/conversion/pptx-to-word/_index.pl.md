---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPTX na Word w C++
url: /pl/cpp/conversion/pptx-to-word/
keywords: Konwertuj PPTX na Word, PPTX na Word, PPTX na DOC, PowerPoint na Word, C++ API, C++ Library, CPP
description: Konwertuj PPTX na Word w C++. Użyj interfejsu API biblioteki C++, aby przekonwertować program PowerPoint na program Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPTX na Word w C++" h2="Potężny, wieloplatformowy interfejs API C++ do konwersji programu PowerPoint na Word przy użyciu kodu C++ bez programu Microsoft PowerPoint lub pakietu Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PowerPoint na Word w C++" variant="code" %}}

Możesz szybko przekonwertować PPTX na Word za pomocą zaledwie kilku linii kodu

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod C++ do konwersji programu PowerPoint do programu Word" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PowerPoint na Word za pomocą Aspose.Slides i Aspose.Words" %}}

[**Aspose.Slides dla C++**](https://products.aspose.com/slides/pl/cpp/) i [**Aspose.Words dla C++**](https://products.aspose.com/ Words/cpp/) to potężne biblioteki C++ używane do manipulowania i konwertowania prezentacji programu PowerPoint, dokumentów programu Word i innych plików. Podczas konwertowania programu PowerPoint na program Word zasadniczo przenosisz zawartość slajdów prezentacji na strony w dokumencie programu Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PPTX na Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides dla C++** i **Aspose.Words dla C++**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz instancję klasy Presentation i klasy Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj prezentację PPTX, którą chcesz przekonwertować na format Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Generuj obrazy i teksty na podstawie zawartości slajdów.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynikowy dokument programu Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Darmowy konwerter online"
  description="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także konwertować PowerPoint do plików w innych formatach" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
