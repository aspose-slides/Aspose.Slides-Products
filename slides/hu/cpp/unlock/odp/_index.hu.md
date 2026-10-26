---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-bemutatók feloldása C++ segítségével
url: /hu/cpp/unlock/odp/
description: Oldja fel ODP-bemutatóit C++ nyelven. Az Aspose.Slides for C++ segítségével eltávolíthatja a titkosítást és az írásvédelmet a bemutatófájlokból.
keywords: Írásvédelem eltávolítása ODP, ODP visszafejtése, ODP-bemutató feloldása, ODP védelmének megszüntetése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP feloldása C++ segítségével" h2="Az Aspose.Slides for C++ segítségével a Microsoft PowerPoint nélkül távolíthatja el a titkosítást és az írásvédelmet a bemutatófájlokból." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Védelem eltávolítása ODP-bemutatóból C++ segítségével" variant="code" %}}

Az Aspose.Slides for C++ segítségével eltávolíthatja a titkosítást vagy az írásvédelmet ODP-bemutatókból. Titkosított fájl megnyitásához használja a `LoadOptions` osztályt, majd a `Presentation` osztály `ProtectionManager` objektumán keresztül hívja meg a `RemoveEncryption` vagy a `RemoveWriteProtection` metódust.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Jelszavas védelem eltávolítása ODP-ből C++ segítségével" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem eltávolítása ODP-bemutatóból C++ segítségével" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jelszó eltávolítása ODP-ből C++ segítségével" intro="Kövesse az alábbi lépéseket a védelem eltávolításához egy ODP-bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP-fájlt a `Presentation` osztállyal, és ha jelszó szükséges, a `LoadOptions` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A védelem eltávolításához használja a `ProtectionManager` objektumot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Titkosított fájloknál hívja meg a `RemoveEncryption`, írásvédett fájloknál a `RemoveWriteProtection` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a feloldott fájlt a `SaveFormat::Odp` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Az Aspose.Slides segítségével készült" title="ODP-fájlok feloldása online" description="Az ingyenes Aspose.Slides Unlock alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Unlock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a védelmet, mielőtt kódot írna.
- Távolítsa el a jelszót vagy az írásvédelmet a ODP-fájlból.
- Töltse le a feloldott fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a feloldáshoz" subTitle="C++ segítségével a következő formátumokból is eltávolíthatja a védelmet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
