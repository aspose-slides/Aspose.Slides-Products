---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-bemutatófájlok védelme .NET segítségével
url: /hu/net/protect/pptx/
description: C#-forráskód PPTX-bemutatók jelszavas védelméhez.
keywords: PPTX írásvédelem, PPTX titkosítása, PPTX-bemutató zárolása, PPTX védelme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-fájlok zárolása vagy jelszavas védelme C# segítségével" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal titkosítják a bemutatókat és korlátozzák a módosításukat." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTX-bemutató védelme C# segítségével" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével titkosíthat egy PPTX-bemutatót, vagy jelszóval korlátozhatja a módosítását. A `ProtectionManager.Encrypt` metódussal titkosított bemutató megnyitásához meg kell adni a jelszót. A `ProtectionManager.SetWriteProtection` használatával a bemutató megnyitható marad, a módosítások azonban korlátozottak.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX-bemutató titkosítása C# segítségével" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem beállítása PPTX-bemutatóhoz C# segítségével" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX-bemutató jelszavas védelme C# segítségével" intro="Kövesse az alábbi lépéseket egy PPTX-bemutató jelszavas védelméhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX-fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Titkosítsa a bemutatót a `ProtectionManager.Encrypt` metódussal, vagy korlátozza a módosításokat a `ProtectionManager.SetWriteProtection` metódussal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a védett fájlt a `SaveFormat.Pptx` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Az Aspose.Slides segítségével készült" title="PPTX-fájlok jelszavas védelme online" description="Az ingyenes Aspose.Slides Lock alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Lock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan védi az Aspose.Slides a bemutatókat, mielőtt kódot írna.
- Állítson be jelszót a PPTX-fájl megnyitásához vagy szerkesztéséhez.
- Töltse le a védett fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a védelemhez" subTitle="C# segítségével a következő formátumokat is védheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
