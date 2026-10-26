---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-bemutatófájlok feloldása Java segítségével
url: /hu/java/unlock/odp/
description: Távolítsa el a jelszavakat és az írásvédelmet ODP-bemutatókból Java nyelven az Aspose.Slides for Java segítségével.
keywords: Írásvédelem eltávolítása ODP, ODP visszafejtése, ODP-bemutató feloldása, ODP védelmének megszüntetése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP feloldása Java segítségével" h2="Készítsen Java-alkalmazásokat, amelyek kiszolgálóoldali API-kkal távolítják el a jelszavakat és az írásvédelmet a bemutatófájlokból." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Védelem eltávolítása ODP-bemutatóból Java segítségével" variant="code" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével eltávolíthatja a titkosítást vagy az írásvédelmet egy ODP-bemutatóból. Titkosított bemutató megnyitásához használja a `LoadOptions.setPassword` metódust, a védelmi beállítások eltávolításához pedig a `ProtectionManager` `removeEncryption` és `removeWriteProtection` metódusát.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Jelszavas védelem eltávolítása ODP-ből Java segítségével" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem eltávolítása ODP-bemutatóból Java segítségével" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jelszó eltávolítása ODP-ből Java segítségével" intro="Kövesse az alábbi lépéseket a védelem eltávolításához egy ODP-bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP-fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ha a bemutató titkosított, használja a `LoadOptions.setPassword` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `ProtectionManager` objektum `removeEncryption` vagy `removeWriteProtection` metódusát.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a feloldott bemutatót a `SaveFormat.Odp` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Az Aspose.Slides segítségével készült" title="ODP-fájlok feloldása online" description="Az ingyenes Aspose.Slides Unlock alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Unlock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a védelmet, mielőtt kódot írna.
- Távolítsa el a jelszót vagy az írásvédelmet a ODP-fájlból.
- Töltse le a feloldott fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a feloldáshoz" subTitle="Java segítségével a következő formátumokból is eltávolíthatja a védelmet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
