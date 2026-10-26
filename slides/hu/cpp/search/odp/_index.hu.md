---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Szöveg keresése ODP bemutatókban C++ használatával
url: /hu/cpp/search/odp/
description: Szöveg keresése ODP bemutatókban C++ nyelven. Az Aspose.Slides for C++ segítségével szöveget találhat bemutatófájlokban.
keywords: szavak keresése ODP fájlban, szöveg megtalálása ODP fájlban, ODP bemutató szövegének keresése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Szöveg keresése ODP fájlban C++ használatával" h2="Az Aspose.Slides for C++ segítségével Microsoft PowerPoint nélkül találhat szöveget bemutatófájlokban." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szöveg keresése ODP bemutatóban C++ segítségével" variant="code" %}}

Az Aspose.Slides for C++ segítségével szöveget kereshet ODP bemutatókban. Gyűjtse össze egy dia szövegkereteit a `SlideUtil::GetAllTextBoxes` segítségével, majd ellenőrizze, hogy a szövegük tartalmazza-e a kívánt kifejezést.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveg keresése ODP bemutatóban C++ használatával" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan kereshet szöveget ODP fájlban C++ segítségével" intro="Az alábbi lépésekkel kereshet szöveget egy ODP bemutatóban." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a kívánt diát a `Presentation::get_Slides` segítségével, a szövegkereteit pedig a [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ellenőrizze, hogy az egyes keretek szövege tartalmazza-e a kívánt kifejezést.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Az Aspose.Slides segítségével készült" title="Szöveg keresése ODP fájlokban online" description="Az ingyenes Aspose.Slides Search alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Search megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan talál szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen egyszerű szöveget vagy reguláris kifejezéseket a ODP fájlban.
- Töltse le a találatokat szövegfájlként.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kereséshez" subTitle="C++ használatával a következő formátumokban is kereshet szöveget." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
