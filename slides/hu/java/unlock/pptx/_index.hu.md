---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-bemutatófájlok feloldása Java segítségével
url: /hu/java/unlock/pptx/
description: Távolítsa el a jelszavakat és az írásvédelmet PPTX-bemutatókból Java nyelven az Aspose.Slides for Java segítségével.
keywords: Írásvédelem eltávolítása PPTX, PPTX visszafejtése, PPTX-bemutató feloldása, PPTX védelmének megszüntetése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX feloldása Java segítségével" h2="Készítsen Java-alkalmazásokat, amelyek kiszolgálóoldali API-kkal távolítják el a jelszavakat és az írásvédelmet a bemutatófájlokból." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Védelem eltávolítása PPTX-bemutatóból Java segítségével" variant="code" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével eltávolíthatja a titkosítást vagy az írásvédelmet egy PPTX-bemutatóból. Titkosított bemutató megnyitásához használja a `LoadOptions.setPassword` metódust, a védelmi beállítások eltávolításához pedig a `ProtectionManager` `removeEncryption` és `removeWriteProtection` metódusát.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Jelszavas védelem eltávolítása PPTX-ből Java segítségével" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem eltávolítása PPTX-bemutatóból Java segítségével" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jelszó eltávolítása PPTX-ből Java segítségével" intro="Kövesse az alábbi lépéseket a védelem eltávolításához egy PPTX-bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX-fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ha a bemutató titkosított, használja a `LoadOptions.setPassword` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `ProtectionManager` objektum `removeEncryption` vagy `removeWriteProtection` metódusát.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a feloldott bemutatót a `SaveFormat.Pptx` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Az Aspose.Slides segítségével készült" title="PPTX-fájlok feloldása online" description="Az ingyenes Aspose.Slides Unlock alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Unlock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a védelmet, mielőtt kódot írna.
- Távolítsa el a jelszót vagy az írásvédelmet a PPTX-fájlból.
- Töltse le a feloldott fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a feloldáshoz" subTitle="Java segítségével a következő formátumokból is eltávolíthatja a védelmet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
