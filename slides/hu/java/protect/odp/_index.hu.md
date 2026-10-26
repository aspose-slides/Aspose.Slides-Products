---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-bemutatófájlok védelme Java segítségével
url: /hu/java/protect/odp/
description: Védje ODP-bemutatóit Java nyelven. Az Aspose.Slides for Java segítségével titkosíthatja a bemutatófájlokat, és írásvédelmet állíthat be.
keywords: Írásvédelem ODP, ODP titkosítása, ODP-bemutató zárolása, ODP védelme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP zárolása vagy jelszavas védelme Java segítségével" h2="Készítsen Java-alkalmazásokat, amelyek kiszolgálóoldali API-kkal védik a bemutatófájlokat." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP-bemutató védelme Java segítségével" variant="code" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével jelszó beállításával megvédheti a ODP-bemutatót a megnyitástól vagy a módosítástól. A `Presentation` osztály `ProtectionManager` objektumán keresztül hívja meg például az `encrypt` és a `setWriteProtection` metódust.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP-bemutató titkosítása Java segítségével" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem beállítása ODP-bemutatóhoz Java segítségével" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="ODP jelszavas védelme Java segítségével" intro="Kövesse az alábbi lépéseket egy ODP-bemutató védelméhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP-fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `ProtectionManager` objektum `encrypt` vagy `setWriteProtection` metódusát.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a védett fájlt a `SaveFormat.Odp` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Az Aspose.Slides segítségével készült" title="ODP-fájlok jelszavas védelme online" description="Az ingyenes Aspose.Slides Lock alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Lock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan védi az Aspose.Slides a bemutatókat, mielőtt kódot írna.
- Állítson be jelszót a ODP-fájl megnyitásához vagy szerkesztéséhez.
- Töltse le a védett fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a védelemhez" subTitle="Java segítségével a következő formátumokat is védheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
