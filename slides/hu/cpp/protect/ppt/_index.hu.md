---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT-bemutatók védelme C++ segítségével
url: /hu/cpp/protect/ppt/
description: Védje PPT-bemutatóit C++ nyelven. Az Aspose.Slides for C++ segítségével titkosíthatja a fájlokat, és írásvédelmet állíthat be.
keywords: Írásvédelem PPT, PPT titkosítása, PPT-bemutató zárolása, PPT védelme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT zárolása vagy jelszavas védelme C++ segítségével" h2="Az Aspose.Slides for C++ segítségével titkosíthatja a bemutatókat és írásvédelmet állíthat be a Microsoft PowerPoint nélkül." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPT-bemutató védelme C++ segítségével" variant="code" %}}

Az Aspose.Slides for C++ segítségével megvédheti a PPT-bemutatókat a megnyitástól vagy a módosítástól. A `Presentation` osztály `ProtectionManager` objektumával titkosíthatja a fájlt az `Encrypt` metódussal, vagy korlátozhatja a szerkesztést a `SetWriteProtection` metódussal.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT-bemutató titkosítása C++ segítségével" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Írásvédelem beállítása PPT-bemutatóhoz C++ segítségével" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPT jelszavas védelme C++ segítségével" intro="Kövesse az alábbi lépéseket egy PPT-bemutató védelméhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPT-fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Védje a bemutatót a `ProtectionManager` objektummal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Jelszavas védelemhez használja az `Encrypt`, írásvédelemhez a `SetWriteProtection` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a védett fájlt a `SaveFormat::Ppt` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Az Aspose.Slides segítségével készült" title="PPT-fájlok jelszavas védelme online" description="Az ingyenes Aspose.Slides Lock alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPT fájljaival." button="Aspose.Slides Lock megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan védi az Aspose.Slides a bemutatókat, mielőtt kódot írna.
- Állítson be jelszót a PPT-fájl megnyitásához vagy szerkesztéséhez.
- Töltse le a védett fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok a védelemhez" subTitle="C++ segítségével a következő formátumokat is védheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
