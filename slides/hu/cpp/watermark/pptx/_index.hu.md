---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vízjel hozzáadása PPTX bemutatókhoz C++-ban
url: /hu/cpp/watermark/pptx/
description: Adjon szöveges vagy képes vízjelet PPTX bemutatókhoz C++-ban. Az Aspose.Slides for C++ segítségével vízjelet helyezhet el a bemutató diáin.
keywords: vízjel hozzáadása PPTX fájlhoz, szöveges vízjel PPTX, képes vízjel PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vízjel hozzáadása PPTX bemutatóhoz C++-ban" h2="Az Aspose.Slides for C++ segítségével Microsoft PowerPoint nélkül adhat szöveges vagy képes vízjelet bemutatófájlokhoz." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vízjel hozzáadása PPTX bemutatóhoz C++ segítségével" variant="code" %}}

Az Aspose.Slides for C++ segítségével szöveges vagy képes vízjelet adhat PPTX bemutatókhoz. Adjon vízjel-alakzatot a diamintához az `AddAutoShape` metódussal, adjon hozzá szöveget az `AddTextFrame` metódussal, vagy töltse ki az alakzatot a `File::ReadAllBytes` és az `AddImage` segítségével betöltött képpel.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveges vízjel hozzáadása PPTX fájlhoz C++-ban" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Képes vízjel hozzáadása PPTX bemutatóhoz C++-ban" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Vízjel hozzáadása PPTX fájlhoz C++-ban lépésről lépésre" intro="Kövesse az alábbi lépéseket szöveges vagy képes vízjel hozzáadásához PPTX fájlokhoz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Válassza ki a diamintát a `Presentation::get_Masters` gyűjteményből.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá vízjel-alakzatot az `AddAutoShape` metódussal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a vízjel szövegét az `AddTextFrame` metódussal, vagy állítson be képkitöltést az `AddImage` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a vízjeles fájlt a `SaveFormat::Pptx` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Az Aspose.Slides segítségével készült" title="Vízjel hozzáadása PPTX fájlokhoz online" description="Az ingyenes Aspose.Slides Watermark alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Watermark megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan adja hozzá az Aspose.Slides a vízjeleket, mielőtt kódot írna.
- Adjon szöveges vagy képes vízjelet PPTX fájljához.
- Töltse le a vízjeles fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További vízjelet támogató formátumok" subTitle="C++-ban a következő formátumokhoz is adhat vízjelet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
