---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSX metaadatok megtekintése és szerkesztése C++-ban
url: /hu/cpp/metadata/ppsx/
description: PPSX metaadatok megtekintése és szerkesztése C++-ban. Az Aspose.Slides for C++ segítségével frissítheti a bemutatók beépített és egyéni tulajdonságait.
keywords: PPSX metaadatok szerkesztése, PPSX metaadatok megtekintése, PPSX tulajdonságok szerkesztése, PPSX tulajdonságok megtekintése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSX metaadatok szerkesztése C++-ban" h2="Az Aspose.Slides for C++ segítségével megtekintheti és frissítheti a bemutatófájlok beépített és egyéni tulajdonságait." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSX tulajdonságok módosítása C++-ban" variant="code" %}}

Az Aspose.Slides for C++ segítségével Microsoft PowerPoint nélkül olvashatja és frissítheti a PPSX fájlok metaadatait. A `Presentation::get_DocumentProperties` által elérhető [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) objektummal módosíthatja a beépített tulajdonságokat, például az `Author` és `Title` értékét, vagy kezelheti az egyéni tulajdonságokat az `idx_set`, `GetCustomPropertyName` és `RemoveCustomProperty` segítségével.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX beépített tulajdonságainak módosítása – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppsx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.ppsx", SaveFormat::Ppsx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Egyéni tulajdonságok hozzáadása PPSX fájlhoz – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppsx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.ppsx", SaveFormat::Ppsx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPSX metaadatok megtekintése és szerkesztése C++-ban lépésről lépésre" intro="Kövesse az alábbi lépéseket a PPSX metaadatok megtekintéséhez vagy szerkesztéséhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPSX fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a `DocumentProperties` objektumot a `get_DocumentProperties` metódussal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Olvassa ki vagy frissítse a beépített tulajdonságokat, például `Author` és `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá, olvasson ki vagy távolítson el egyéni tulajdonságokat az `idx_set`, `GetCustomPropertyName` és `RemoveCustomProperty` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Az Aspose.Slides segítségével készült" title="PPSX metaadatok megtekintése és szerkesztése online" description="Az ingyenes Aspose.Slides Metadata alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPSX fájljaival." button="Aspose.Slides Metadata megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa és írja az Aspose.Slides a tulajdonságokat, mielőtt kódot írna.
- Tekintse meg és szerkessze PPSX fájlja beépített és egyéni tulajdonságait.
- Mentse és töltse le a frissített fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott metaadatformátumok" subTitle="C++-ban a következő formátumok metaadatait is kezelheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
