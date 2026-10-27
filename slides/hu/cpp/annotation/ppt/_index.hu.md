---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Jegyzetek eltávolítása PPT fájlból C++ segítségével
url: /hu/cpp/annotation/ppt/ 
description: C++ forráskód jegyzetek eltávolításához PPT bemutatókból.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Megjegyzések és szerzőik eltávolítása PPT fájlból C++ nyelven" h2="Készítsen C++-alkalmazásokat, amelyek kiszolgálóoldali API-kkal kezelik a bemutatófájlok megjegyzéseit és szerzőit." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Megjegyzések eltávolítása PPT fájlból C++ segítségével" variant="code" %}}

Az [Aspose.Slides for C++](/slides/hu/cpp/) segítségével eltávolíthatja a megjegyzéseket és szerzőiket PPT bemutatókból. Az alábbi példa törli a `get_CommentAuthors` által visszaadott minden szerző megjegyzéseit, majd kiüríti a megjegyzésszerzők gyűjteményét.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Jegyzetek törlése PPT fájlból – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.ppt");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan távolíthatók el a megjegyzések PPT fájlból C++ segítségével" intro="Az alábbi lépésekkel eltávolíthatja a megjegyzéseket és szerzőiket egy PPT bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Aspose.Slides for C++ csomagot. Lásd: [Telepítés](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPT fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haladjon végig a `get_CommentAuthors` által visszaadott megjegyzésszerzőkön.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Törölje minden szerző megjegyzéseit a `get_Comments()->Clear()` hívással.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ürítse ki a megjegyzésszerzők gyűjteményét.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a frissített bemutatót a `SaveFormat::Ppt` értékkel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Az Aspose.Slides segítségével készült" title="Megjegyzések eltávolítása PPT fájlból online" description="Az ingyenes Aspose.Slides Annotation alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPT fájljaival." button="Aspose.Slides Annotation megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a megjegyzéseket, mielőtt kódot írna.
- Távolítsa el az összes megjegyzést a PPT fájlból.
- Töltse le a megtisztított fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok jegyzetekhez" subTitle="C++ használatával más formátumokból is eltávolíthatja a jegyzeteket." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
