---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSM metaadatok megtekintése és szerkesztése Pythonnal
url: /hu/python-net/metadata/ppsm/
description: PPSM fájlok beépített és egyéni metaadat-tulajdonságainak megtekintése és szerkesztése Pythonnal.
keywords: PPSM metaadatok szerkesztése, PPSM metaadatok megtekintése, PPSM tulajdonságok szerkesztése, PPSM tulajdonságok megtekintése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSM metaadatok megtekintése és szerkesztése Pythonnal – példa" h2="Készítsen Python-alkalmazásokat, amelyek az Aspose.Slides segítségével olvassák és módosítják a bemutatók beépített és egyéni tulajdonságait." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSM metaadatok megtekintése és módosítása Pythonnal" variant="code" %}}

Az [**Aspose.Slides for Python via .NET**](/slides/hu/python-net/) segítségével olvashatja és frissítheti a beépített metaadatokat, valamint egyéni dokumentumtulajdonságokat adhat hozzá, frissíthet vagy távolíthat el a PPSM bemutatókban. A `Presentation.document_properties` révén érje el az [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) objektumot, módosítsa, majd mentse a bemutatót PPSM formátumban.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM beépített tulajdonságainak frissítése – Python" >}}
```python
with slides.Presentation("presentation.ppsm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.ppsm", slides.export.SaveFormat.PPSM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM egyéni tulajdonságainak hozzáadása és eltávolítása – Python" >}}
```python
with slides.Presentation("presentation.ppsm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.ppsm", slides.export.SaveFormat.PPSM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPSM metaadatok szerkesztése Pythonnal lépésről lépésre" intro="Kövesse az alábbi lépéseket egy PPSM fájl metaadatainak szerkesztéséhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a PPSM fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Érje el az `IDocumentProperties` objektumot a `Presentation.document_properties` révén.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Frissítse a beépített tulajdonságokat, vagy az egyéni tulajdonságokhoz használja a `set_custom_property_value` és `remove_custom_property` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a bemutatót a `Presentation.save` és a `SaveFormat.PPSM` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Az Aspose.Slides segítségével készült" title="PPSM metaadatok megtekintése és szerkesztése online" description="Az ingyenes Aspose.Slides Metadata alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPSM fájljaival." button="Aspose.Slides Metadata megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa és írja az Aspose.Slides a tulajdonságokat, mielőtt kódot írna.
- Tekintse meg és szerkessze PPSM fájlja beépített és egyéni tulajdonságait.
- Mentse és töltse le a frissített fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott metaadatformátumok" subTitle="Pythonnal más támogatott bemutatóformátumok metaadatait is kezelheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
