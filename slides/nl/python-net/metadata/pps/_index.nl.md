---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPS-metadata bekijken of bewerken met Python
url: /nl/python-net/metadata/pps/
description: Bekijk en bewerk ingebouwde en aangepaste metadata-eigenschappen in PPS-bestanden met Python.
keywords: PPS-metadata bewerken, PPS-metadata bekijken, PPS-eigenschappen bewerken, PPS-eigenschappen bekijken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPS-metadata bekijken en bewerken met Python" h2="Bouw Python-toepassingen die met Aspose.Slides ingebouwde en aangepaste presentatie-eigenschappen lezen en wijzigen." related="FODP,ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPS-metadata bekijken en wijzigen met Python" variant="code" %}}

Met [**Aspose.Slides for Python via .NET**](/slides/nl/python-net/) leest en wijzigt u ingebouwde metadata en voegt u aangepaste documenteigenschappen in PPS-presentaties toe, wijzigt u ze of verwijdert u ze. Open een [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/)-object via `Presentation.document_properties`, wijzig het en sla de presentatie op in PPS-formaat.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ingebouwde PPS-eigenschappen bijwerken – Python" >}}
```python
with slides.Presentation("presentation.pps") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.pps", slides.export.SaveFormat.PPS)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aangepaste PPS-eigenschappen toevoegen en verwijderen – Python" >}}
```python
with slides.Presentation("presentation.pps") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.pps", slides.export.SaveFormat.PPS)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPS-metadata bewerken met Python" intro="Volg deze stappen om de metadata van een PPS-bestand te bewerken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open het PPS-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open het `IDocumentProperties`-object via `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Werk ingebouwde eigenschappen bij of gebruik `set_custom_property_value` en `remove_custom_property` voor aangepaste eigenschappen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de presentatie op met `Presentation.save` en `SaveFormat.PPS`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Gebouwd met Aspose.Slides" title="PPS-metadata online bekijken en bewerken" description="De gratis app Aspose.Slides Metadata is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPS-bestanden." button="Aspose.Slides Metadata openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides eigenschappen leest en schrijft voordat u code schrijft.
- Bekijk en bewerk de ingebouwde en aangepaste eigenschappen van uw PPS-bestand.
- Sla het bijgewerkte bestand op en download het.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde metadataformaten" subTitle="Met Python kunt u ook de metadata van andere ondersteunde presentatieformaten beheren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
