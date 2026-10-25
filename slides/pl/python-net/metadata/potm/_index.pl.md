---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyświetlanie i edycja metadanych POTM w Pythonie
url: /pl/python-net/metadata/potm/
description: Wyświetlaj i edytuj wbudowane i niestandardowe właściwości metadanych w plikach POTM w Pythonie.
keywords: edycja metadanych POTM, wyświetlanie metadanych POTM, edycja właściwości POTM, wyświetlanie właściwości POTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wyświetlanie i edycja metadanych POTM w Pythonie – przykład" h2="Twórz aplikacje w Pythonie, które za pomocą Aspose.Slides odczytują i modyfikują wbudowane i niestandardowe właściwości prezentacji." related="FODP,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wyświetlanie i modyfikacja metadanych POTM w Pythonie" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/pl/python-net/) pozwala odczytywać i aktualizować wbudowane metadane oraz dodawać, aktualizować i usuwać niestandardowe właściwości dokumentu w prezentacjach POTM. Uzyskaj dostęp do obiektu [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) przez `Presentation.document_properties`, zmodyfikuj go i zapisz prezentację w formacie POTM.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aktualizacja wbudowanych właściwości POTM – Python" >}}
```python
with slides.Presentation("presentation.potm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.potm", slides.export.SaveFormat.POTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie i usuwanie niestandardowych właściwości POTM – Python" >}}
```python
with slides.Presentation("presentation.potm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.potm", slides.export.SaveFormat.POTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak edytować metadane POTM w Pythonie" intro="Wykonaj poniższe kroki, aby edytować metadane pliku POTM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz plik POTM za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uzyskaj dostęp do obiektu `IDocumentProperties` przez `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zaktualizuj wbudowane właściwości lub użyj `set_custom_property_value` i `remove_custom_property` dla właściwości niestandardowych.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz prezentację za pomocą `Presentation.save` i `SaveFormat.POTM`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Zbudowano z Aspose.Slides" title="Wyświetlaj i edytuj metadane POTM online" description="Bezpłatna aplikacja Aspose.Slides Metadata została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami POTM." button="Otwórz Aspose.Slides Metadata" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides odczytuje i zapisuje właściwości, zanim napiszesz kod.
- Wyświetlaj i edytuj wbudowane i niestandardowe właściwości pliku POTM.
- Zapisz i pobierz zaktualizowany plik.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty metadanych" subTitle="W Pythonie możesz też zarządzać metadanymi innych obsługiwanych formatów prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
