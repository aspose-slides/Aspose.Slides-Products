---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-bemutatófájlok védelme .NET segítségével
url: /hu/net/protect/odp/
description: C#-forráskód ODP-bemutatók jelszavas védelméhez.
keywords: ODP írásvédelem, ODP titkosítása, ODP-bemutató zárolása, ODP védelme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-fájlok zárolása vagy jelszavas védelme C# segítségével" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal titkosítják a bemutatókat és korlátozzák a módosításukat." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP-bemutató védelme C# segítségével" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével titkosíthat egy ODP-bemutatót, vagy jelszóval korlátozhatja a módosítását. A `ProtectionManager.Encrypt` metódussal titkosított bemutató megnyitásához meg kell adni a jelszót. A `ProtectionManager.SetWriteProtection` használatával a bemutató megnyitható marad, a módosítások azonban korlátozottak.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP-bemutató titkosítása C# segítségével" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem beállítása ODP-bemutatóhoz C# segítségével" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="ODP-bemutató jelszavas védelme C# segítségével" intro="Kövesse az alábbi lépéseket egy ODP-bemutató jelszavas védelméhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP-fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Titkosítsa a bemutatót a `ProtectionManager.Encrypt` metódussal, vagy korlátozza a módosításokat a `ProtectionManager.SetWriteProtection` metódussal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a védett fájlt a `SaveFormat.Odp` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Az Aspose.Slides segítségével készült" title="ODP-fájlok jelszavas védelme online" description="Az ingyenes Aspose.Slides Lock alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Lock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan védi az Aspose.Slides a bemutatókat, mielőtt kódot írna.
- Állítson be jelszót a ODP-fájl megnyitásához vagy szerkesztéséhez.
- Töltse le a védett fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a védelemhez" subTitle="C# segítségével a következő formátumokat is védheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
