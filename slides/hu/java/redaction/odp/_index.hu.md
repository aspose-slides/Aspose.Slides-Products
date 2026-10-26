---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP bemutatófájlok kitakarása Java használatával
url: /hu/java/redaction/odp/
description: Szöveg keresése és cseréje ODP bemutatókban Java nyelven az Aspose.Slides for Java segítségével.
keywords: ODP kitakarása, szöveg keresése és cseréje ODP fájlban, ODP bemutató frissítése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP kitakarása Java használatával" h2="Készítsen Java-alkalmazásokat, amelyek kiszolgálóoldali API-kkal keresnek és cserélnek szöveget bemutatófájlokban." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP bemutató kitakarása Java segítségével" variant="code" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével szöveget kereshet és cserélhet ODP bemutatókban. A `SlideUtil.findAndReplaceText` metódussal keresse át a bemutatót, és cserélje le az egyező szöveget egy új értékre.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP bemutató kitakarása Java használatával" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan takarható ki egy ODP fájl Java segítségével" intro="Az alábbi lépésekkel takarhat ki egy ODP bemutatót." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `SlideUtil.findAndReplaceText` metódust a szöveg kereséséhez és cseréjéhez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a frissített bemutatót a `SaveFormat.Odp` értékkel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Az Aspose.Slides segítségével készült" title="ODP fájlok kitakarása online" description="Az ingyenes Aspose.Slides Redaction alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Redaction megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan keres és cserél szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen és cseréljen szöveget a ODP fájlban, akár reguláris kifejezésekkel is.
- Töltse le a kitakart fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kitakaráshoz" subTitle="Java használatával a következő formátumokat is kitakarhatja." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
