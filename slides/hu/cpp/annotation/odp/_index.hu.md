---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Jegyzetek eltávolítása ODP fájlból C++ segítségével
url: /hu/cpp/annotation/odp/ 
description: C++ forráskód jegyzetek eltávolításához ODP bemutatókból.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Megjegyzések és szerzőik eltávolítása ODP fájlból C++ nyelven" h2="Készítsen C++-alkalmazásokat, amelyek kiszolgálóoldali API-kkal kezelik a bemutatófájlok megjegyzéseit és szerzőit." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Megjegyzések eltávolítása ODP fájlból C++ segítségével" variant="code" %}}

Az [Aspose.Slides for C++](/slides/hu/cpp/) segítségével eltávolíthatja a megjegyzéseket és szerzőiket ODP bemutatókból. Az alábbi példa törli a `get_CommentAuthors` által visszaadott minden szerző megjegyzéseit, majd kiüríti a megjegyzésszerzők gyűjteményét.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Jegyzetek törlése ODP fájlból – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.odp");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan távolíthatók el a megjegyzések ODP fájlból C++ segítségével" intro="Az alábbi lépésekkel eltávolíthatja a megjegyzéseket és szerzőiket egy ODP bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Aspose.Slides for C++ csomagot. Lásd: [Telepítés](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haladjon végig a `get_CommentAuthors` által visszaadott megjegyzésszerzőkön.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Törölje minden szerző megjegyzéseit a `get_Comments()->Clear()` hívással.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ürítse ki a megjegyzésszerzők gyűjteményét.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a frissített bemutatót a `SaveFormat::Odp` értékkel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Az Aspose.Slides segítségével készült" title="Megjegyzések eltávolítása ODP fájlból online" description="Az ingyenes Aspose.Slides Annotation alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Annotation megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a megjegyzéseket, mielőtt kódot írna.
- Távolítsa el az összes megjegyzést a ODP fájlból.
- Töltse le a megtisztított fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok jegyzetekhez" subTitle="C++ használatával más formátumokból is eltávolíthatja a jegyzeteket." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
