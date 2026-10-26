---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-bemutatók védelme C++ segítségével
url: /hu/cpp/protect/pptx/
description: Védje PPTX-bemutatóit C++ nyelven. Az Aspose.Slides for C++ segítségével titkosíthatja a fájlokat, és írásvédelmet állíthat be.
keywords: Írásvédelem PPTX, PPTX titkosítása, PPTX-bemutató zárolása, PPTX védelme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX zárolása vagy jelszavas védelme C++ segítségével" h2="Az Aspose.Slides for C++ segítségével titkosíthatja a bemutatókat és írásvédelmet állíthat be a Microsoft PowerPoint nélkül." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTX-bemutató védelme C++ segítségével" variant="code" %}}

Az Aspose.Slides for C++ segítségével megvédheti a PPTX-bemutatókat a megnyitástól vagy a módosítástól. A `Presentation` osztály `ProtectionManager` objektumával titkosíthatja a fájlt az `Encrypt` metódussal, vagy korlátozhatja a szerkesztést a `SetWriteProtection` metódussal.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX-bemutató titkosítása C++ segítségével" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem beállítása PPTX-bemutatóhoz C++ segítségével" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX jelszavas védelme C++ segítségével" intro="Kövesse az alábbi lépéseket egy PPTX-bemutató védelméhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX-fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Védje a bemutatót a `ProtectionManager` objektummal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Jelszavas védelemhez használja az `Encrypt`, írásvédelemhez a `SetWriteProtection` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a védett fájlt a `SaveFormat::Pptx` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Az Aspose.Slides segítségével készült" title="PPTX-fájlok jelszavas védelme online" description="Az ingyenes Aspose.Slides Lock alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Lock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan védi az Aspose.Slides a bemutatókat, mielőtt kódot írna.
- Állítson be jelszót a PPTX-fájl megnyitásához vagy szerkesztéséhez.
- Töltse le a védett fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a védelemhez" subTitle="C++ segítségével a következő formátumokat is védheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
