---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Jegyzetek eltávolítása ODP fájlból .NET segítségével
url: /hu/net/annotation/odp/ 
description: Távolítsa el a megjegyzéseket és a megjegyzések szerzőit ODP bemutatókból C# nyelven.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Megjegyzések és szerzőik eltávolítása ODP fájlból C# nyelven" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal kezelik a bemutatófájlok megjegyzéseit és szerzőit." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Megjegyzések eltávolítása ODP fájlból C# segítségével" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével eltávolíthatja a megjegyzéseket és szerzőiket a ODP bemutatófájlokból. Az alábbi példa kiüríti minden szerző `Comments` gyűjteményét, majd a bemutató `CommentAuthors` gyűjteményét.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Jegyzetek törlése ODP fájlból – C#" >}}
```cs
using var presentation = new Presentation("example.odp");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan távolíthatók el a megjegyzések ODP fájlból C# segítségével" intro="Az alábbi lépésekkel eltávolíthatja a megjegyzéseket és szerzőiket egy ODP bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Aspose.Slides for .NET csomagot. Lásd: [Telepítés](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haladjon végig a `CommentAuthors` gyűjteményen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ürítse ki minden megjegyzésszerző `Comments` gyűjteményét.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ürítse ki a `CommentAuthors` gyűjteményt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a frissített bemutatót a `SaveFormat.Odp` értékkel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Az Aspose.Slides segítségével készült" title="Megjegyzések eltávolítása ODP fájlból online" description="Az ingyenes Aspose.Slides Annotation alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Annotation megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a megjegyzéseket, mielőtt kódot írna.
- Távolítsa el az összes megjegyzést a ODP fájlból.
- Töltse le a megtisztított fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok jegyzetekhez" subTitle="C# használatával más formátumokból is eltávolíthatja a jegyzeteket." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
