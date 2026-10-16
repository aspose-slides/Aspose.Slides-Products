---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JPG konvertálása PPT-re C++ nyelven
url: /hu/cpp/conversion/jpg-to-ppt/
keywords: JPG konvertálása PPT-vé, JPG konvertálása PPT-vé, PowerPoint, JPG, PPT, C++ API, C++ Library
description: JPG konvertálása PPT-re C++ nyelven. Használja a C++ könyvtár API-t a JPG képek PowerPoint formátumba konvertálásához
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JPG konvertálása PPT-re C++ nyelven" h2="Hatékony, többplatformos C++ API JPG konvertálásához PPT-vé C++ kód használatával" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JPG konvertálása PPT-re C++ nyelven" variant="code" %}}

Az [**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) segítségével néhány sornyi kóddal JPG-képet PowerPoint prezentációvá konvertálhat:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ kód a JPG PPT-vé konvertálásához" >}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a JPG-t PPT-vé az Aspose.Slides segítségével" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) egy hatékony C++-könyvtár, amellyel PowerPoint-prezentációkat, PDF-eket, HTML-dokumentumokat és egyebeket hozhatnak létre, konvertálhatnak és kezelhetnek. fájlokat. Amikor JPG-t PPT-vé konvertál, lényegében egy PowerPoint bemutatót hoz létre, amely JPG képeken alapuló diákat tartalmaz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan lehet JPG-t PPT-vé konvertálni C++-ban" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az **Aspose.Slides for C++** alkalmazást. Lásd: [**Telepítés**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a könyvtárat referenciaként a projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy példányt a Prezentáció osztályból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPT-vé konvertálni kívánt JPG-képet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse el az eredményül kapott fájlt PPT-bemutatóként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes online konverter"
  description="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott PowerPoint-konverziók" subTitle="Más formátumú fájlokat is konvertálhat PowerPointba" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
