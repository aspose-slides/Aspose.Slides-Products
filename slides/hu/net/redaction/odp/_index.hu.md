---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP bemutatófájlok kitakarása .NET segítségével
url: /hu/net/redaction/odp/
description: C# forráskód szöveg kereséséhez és cseréjéhez ODP bemutatókban.
keywords: ODP kitakarása, szöveg keresése és cseréje ODP fájlban, ODP bemutató frissítése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP fájlok kitakarása C# használatával" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal keresnek és cserélnek szöveget bemutatókban." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP bemutató kitakarása C# használatával" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével szöveget kereshet és cserélhet egy ODP bemutatóban. A keresést a `Presentation.ReplaceText` és a `TextSearchOptions` segítségével szabályozhatja, majd mentse a módosított bemutatót.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP bemutató kitakarása C# használatával" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan takarható ki egy ODP bemutató C# használatával" intro="Az alábbi lépésekkel cserélhet szöveget egy ODP bemutatóban." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A kívánt szöveget a [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) és a `TextSearchOptions` segítségével cserélje le.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a módosított bemutatót a `SaveFormat.Odp` értékkel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Az Aspose.Slides segítségével készült" title="ODP fájlok kitakarása online" description="Az ingyenes Aspose.Slides Redaction alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Redaction megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan keres és cserél szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen és cseréljen szöveget a ODP fájlban, akár reguláris kifejezésekkel is.
- Töltse le a kitakart fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kitakaráshoz" subTitle="C# használatával a következő formátumokat is kitakarhatja." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
