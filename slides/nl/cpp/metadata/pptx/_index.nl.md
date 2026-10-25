---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-metadata bekijken of bewerken met C++
url: /nl/cpp/metadata/pptx/
description: Bekijk en bewerk PPTX-metadata in C++. Gebruik Aspose.Slides for C++ om ingebouwde en aangepaste presentatie-eigenschappen bij te werken.
keywords: PPTX-metadata bewerken, PPTX-metadata bekijken, PPTX-eigenschappen bewerken, PPTX-eigenschappen bekijken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-metadata bewerken met C++" h2="Gebruik Aspose.Slides for C++ om ingebouwde en aangepaste eigenschappen in presentatiebestanden te bekijken en bij te werken." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTX-eigenschappen wijzigen via C++" variant="code" %}}

Met Aspose.Slides for C++ leest en wijzigt u metadata in PPTX-bestanden zonder Microsoft PowerPoint. Gebruik het object [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) dat `Presentation::get_DocumentProperties` levert om ingebouwde eigenschappen zoals `Author` en `Title` te wijzigen, of beheer aangepaste eigenschappen met `idx_set`, `GetCustomPropertyName` en `RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ingebouwde PPTX-eigenschappen wijzigen – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aangepaste eigenschappen toevoegen aan PPTX – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX-metadata bekijken of bewerken in C++" intro="Volg deze stappen om PPTX-metadata te bekijken of te bewerken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPTX-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haal het `DocumentProperties`-object op met `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lees of wijzig ingebouwde eigenschappen zoals `Author` en `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg aangepaste eigenschappen toe, lees ze of verwijder ze met `idx_set`, `GetCustomPropertyName` en `RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Gebouwd met Aspose.Slides" title="PPTX-metadata online bekijken en bewerken" description="De gratis app Aspose.Slides Metadata is gebouwd met [Aspose.Slides for C++](https://products.aspose.com/slides/nl/cpp/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Metadata openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides eigenschappen leest en schrijft voordat u code schrijft.
- Bekijk en bewerk de ingebouwde en aangepaste eigenschappen van uw PPTX-bestand.
- Sla het bijgewerkte bestand op en download het.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde metadataformaten" subTitle="Met C++ kunt u ook de metadata van de volgende formaten beheren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/metadata/pptm/" name="PPTM" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
