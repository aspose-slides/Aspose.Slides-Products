---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-bemutatófájlok védelme Python segítségével
url: /hu/python-net/protect/odp/
description: Titkosítsa a ODP-bemutatókat, vagy állítson be írásvédelmet Python segítségével.
keywords: ODP írásvédelem, ODP titkosítása Pythonnal, ODP-bemutató zárolása, ODP védelme Pythonnal
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-bemutatók védelme Python segítségével" h2="Készítsen Python-alkalmazásokat, amelyek az Aspose.Slides segítségével titkosítják a bemutatókat vagy írásvédelmet állítanak be." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP-bemutató védelme Python segítségével" variant="code" %}}

Az [**Aspose.Slides for Python via .NET**](/slides/hu/python-net/) két különböző védelmi mechanizmust kínál. A `ProtectionManager.encrypt` hívásával titkosíthatja a ODP-bemutatót, így annak megnyitásához jelszó szükséges. Másik lehetőségként a `ProtectionManager.set_write_protection` hívásával a fájl titkosítása nélkül tarthatja vissza a felhasználókat a módosítástól. Az írásvédett bemutatót a felhasználó továbbra is megnyithatja, és a módosításokat egy másik fájlba mentheti.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP-bemutató titkosítása – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem beállítása ODP-bemutatón – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="ODP védelme Python segítségével" intro="Kövesse az alábbi lépéseket egy ODP-fájl védelméhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a ODP-fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A `ProtectionManager.encrypt` használatával jelszót követelhet meg a megnyitáshoz, a `ProtectionManager.set_write_protection` használatával pedig visszatarthat a módosításoktól.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a védett bemutatót ODP formátumban a `SaveFormat.ODP` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Az Aspose.Slides segítségével készült" title="ODP-fájlok jelszavas védelme online" description="Az ingyenes Aspose.Slides Lock alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Lock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan védi az Aspose.Slides a bemutatókat, mielőtt kódot írna.
- Állítson be jelszót a ODP-fájl megnyitásához vagy szerkesztéséhez.
- Töltse le a védett fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a védelemhez" subTitle="Python segítségével más támogatott bemutatóformátumokat is védhet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
