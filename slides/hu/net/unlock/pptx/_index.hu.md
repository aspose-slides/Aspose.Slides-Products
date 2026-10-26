---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-bemutatófájlok feloldása .NET segítségével
url: /hu/net/unlock/pptx/
description: C#-forráskód a jelszavas védelem eltávolításához PPTX-bemutatókból.
keywords: PPTX írásvédelem eltávolítása, PPTX visszafejtése, PPTX-bemutató feloldása, PPTX védelmének megszüntetése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-fájlok feloldása C# segítségével" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal távolítják el a titkosítást és az írásvédelmet a bemutatókból." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Védelem eltávolítása PPTX-bemutatóból C# segítségével" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével eltávolíthatja a titkosítást vagy az írásvédelmet egy PPTX-bemutatóból. A titkosítás eltávolításához töltse be a bemutatót a helyes jelszóval, és hívja meg a `ProtectionManager.RemoveEncryption` metódust. Az írásvédelem eltávolításához hívja meg a `ProtectionManager.RemoveWriteProtection` metódust.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Titkosítás eltávolítása PPTX-bemutatóból C# segítségével" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.pptx", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem eltávolítása PPTX-bemutatóból C# segítségével" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.pptx");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan távolítható el a védelem egy PPTX-bemutatóból C# segítségével" intro="Kövesse az alábbi lépéseket a védelem eltávolításához egy PPTX-bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX-fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Titkosított fájl esetén a betöltés előtt adja meg a jelszót a `LoadOptions.Password` tulajdonságban.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az alkalmazott védelemtől függően hívja meg a `ProtectionManager.RemoveEncryption` vagy a `ProtectionManager.RemoveWriteProtection` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a feloldott bemutatót a `SaveFormat.Pptx` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Az Aspose.Slides segítségével készült" title="PPTX-fájlok feloldása online" description="Az ingyenes Aspose.Slides Unlock alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Unlock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a védelmet, mielőtt kódot írna.
- Távolítsa el a jelszót vagy az írásvédelmet a PPTX-fájlból.
- Töltse le a feloldott fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a feloldáshoz" subTitle="C# segítségével a következő formátumokból is eltávolíthatja a védelmet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
