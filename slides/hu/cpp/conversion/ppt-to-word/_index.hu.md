---
title: Konvertálja a PPT-t Word-be C++-ban
url: /hu/cpp/conversion/ppt-to-word/
keywords: Konvertálja a PPT-t Word-be, PPT-t Word-be, PPT-t DOC-ba, PowerPointot Word-be, C++ API-t, C++-könyvtárat, CPP-t
description: Konvertálja a PPT-t Word-be C++-ban. Használja a C++ könyvtár API-t a PowerPoint Wordvé konvertálásához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertálja a PPT-t Word-be C++-ban" h2="Hatékony, többplatformos C++ API a PowerPoint Word-be konvertálásához C++ kóddal Microsoft PowerPoint vagy Office nélkül" >}}

{{% blocks/products/pf/feature-page-section h2="A PowerPoint konvertálása Word-be az Aspose.Slides és az Aspose.Words használatával" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) és [**Aspose.Words for C++**](https://products.aspose.com/ Words/cpp/) olyan hatékony C++-könyvtárak, amelyek PowerPoint-prezentációk, Word-dokumentumok és egyéb fájlok kezelésére és konvertálására szolgálnak. A PowerPoint Word-be konvertálásakor lényegében a prezentáció diákjainak tartalmát egy Word-dokumentum oldalaira helyezi át.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="A PowerPoint konvertálása Word-be C++ nyelven" %}}
Néhány sornyi kóddal gyorsan konvertálhatja a PPT-t Word-be

{{% blocks/products/pf/agp/code-block title="C++ kód a PowerPoint Word-be konvertálásához" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet a PPT-t Word-be konvertálni" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for C++** és **Aspose.Words for C++** alkalmazást 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Presentation osztályból és a Doc osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a Word-be konvertálni kívánt PPT-bemutatót.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A diák tartalma alapján képeket és szövegeket generál.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a kapott Word-dokumentumot.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A PowerPointot más formátumú fájlokká is konvertálhatja" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}