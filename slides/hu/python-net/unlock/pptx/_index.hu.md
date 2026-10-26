---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-bemutatók feloldása Python segítségével
url: /hu/python-net/unlock/pptx/
description: Távolítsa el a titkosítást és az írásvédelmet PPTX-bemutatókból Python segítségével.
keywords: PPTX feloldása, jelszó eltávolítása PPTX-ből, PPTX-titkosítás eltávolítása, írásvédelem eltávolítása PPTX-ből
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-bemutatók feloldása Python segítségével" h2="Készítsen Python-alkalmazásokat, amelyek az Aspose.Slides segítségével távolítják el a megnyitási jelszavakat és az írásvédelmet PPTX-bemutatókból." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Titkosítás és írásvédelem eltávolítása PPTX-ből Python segítségével" variant="code" %}}

Az [Aspose.Slides for Python via .NET](/slides/hu/python-net/) segítségével eltávolíthatja a titkosítást, amely miatt jelszó kell egy PPTX-bemutató megnyitásához, vagy megszüntetheti az írásvédelmét. Titkosított fájl megnyitásához adja meg az aktuális jelszót a `LoadOptions` segítségével.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Titkosítás eltávolítása PPTX-bemutatóból – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem eltávolítása PPTX-bemutatóból – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Védelem eltávolítása PPTX-ből Python segítségével" intro="Kövesse az alábbi lépéseket a védelem eltávolításához egy PPTX-bemutatóból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Titkosított PPTX-fájl esetén adja meg az aktuális jelszót a `LoadOptions` objektumban, majd nyissa meg a fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A megnyitási jelszó eltávolításához hívja meg a `ProtectionManager.remove_encryption`, az írásvédelem megszüntetéséhez a `ProtectionManager.remove_write_protection` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse az eredményül kapott bemutatót a `SaveFormat.PPTX` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Az Aspose.Slides segítségével készült" title="PPTX-fájlok feloldása online" description="Az ingyenes Aspose.Slides Unlock alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Unlock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan távolítja el az Aspose.Slides a védelmet, mielőtt kódot írna.
- Távolítsa el a jelszót vagy az írásvédelmet a PPTX-fájlból.
- Töltse le a feloldott fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a feloldáshoz" subTitle="Python segítségével más támogatott bemutatóformátumokból is eltávolíthatja a védelmet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
