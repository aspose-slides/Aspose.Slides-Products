---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: Jegyzetek eltávolítása ODP fájlból Java segítségével
url: /hu/java/annotation/odp/ 
description: Távolítsa el a megjegyzéseket és szerzőiket ODP bemutatókból Java nyelven az Aspose.Slides for Java segítségével.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Megjegyzések és szerzőik eltávolítása ODP fájlból Java nyelven" h2="Az Aspose.Slides for Java segítségével eltávolíthatja a megjegyzéseket és szerzőiket a bemutatófájlokból." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Megjegyzések eltávolítása ODP fájlból Java segítségével" variant="code" %}}

Az Aspose.Slides for Java segítségével eltávolíthatja a megjegyzéseket és szerzőiket ODP bemutatókból. Töltsön be egy fájlt a `Presentation` osztállyal, haladjon végig a `getCommentAuthors` által visszaadott `ICommentAuthor` objektumokon, törölje a megjegyzéseiket, és mentse a frissített bemutatót.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Jegyzetek törlése ODP fájlból – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan távolíthatók el a megjegyzések ODP fájlból Java segítségével" intro="Az alábbi lépésekkel eltávolíthatja a megjegyzéseket és szerzőiket egy ODP bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Aspose.Slides for Java csomagot. Lásd: [Telepítés](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haladjon végig a `getCommentAuthors` által visszaadott `ICommentAuthor` objektumokon.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Törölje minden szerző megjegyzéseit a `getComments().clear()` hívással.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ürítse ki a megjegyzésszerzők gyűjteményét, és mentse a frissített ODP fájlt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Az Aspose.Slides segítségével készült" title="Megjegyzések eltávolítása ODP fájlból online" description="Az ingyenes Aspose.Slides Annotation alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Annotation megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a megjegyzéseket, mielőtt kódot írna.
- Távolítsa el az összes megjegyzést a ODP fájlból.
- Töltse le a megtisztított fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok jegyzetekhez" subTitle="Java használatával más formátumokból is eltávolíthatja a jegyzeteket." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
