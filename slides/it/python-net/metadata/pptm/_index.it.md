---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Visualizzare o modificare i metadati PPTM con Python
url: /it/python-net/metadata/pptm/
description: Visualizza e modifica le proprietà dei metadati predefinite e personalizzate dei file PPTM con Python.
keywords: Modificare metadati PPTM, visualizzare metadati PPTM, modificare proprietà PPTM, visualizzare proprietà PPTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Visualizzare e modificare i metadati PPTM con Python" h2="Crea applicazioni Python che leggono e modificano le proprietà predefinite e personalizzate delle presentazioni con Aspose.Slides." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Visualizzare e modificare i metadati PPTM in Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/it/python-net/) consente di leggere e aggiornare i metadati predefiniti e di aggiungere, aggiornare o rimuovere proprietà personalizzate del documento nelle presentazioni PPTM. Accedi a un oggetto [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) tramite `Presentation.document_properties`, modificalo e salva la presentazione in formato PPTM.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiornare le proprietà predefinite di PPTM – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere e rimuovere proprietà personalizzate di PPTM – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come modificare i metadati PPTM con Python" intro="Segui questi passaggi per modificare i metadati di un file PPTM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri il file PPTM con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Accedi al suo oggetto `IDocumentProperties` tramite `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiorna le proprietà predefinite oppure usa `set_custom_property_value` e `remove_custom_property` per le proprietà personalizzate.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione con `Presentation.save` e `SaveFormat.PPTM`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Realizzato con Aspose.Slides" title="Visualizzare e modificare i metadati PPTM online" description="L'app gratuita Aspose.Slides Metadata è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTM." button="Apri Aspose.Slides Metadata" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides legge e scrive le proprietà prima di scrivere codice.
- Visualizza e modifica le proprietà predefinite e personalizzate del tuo file PPTM.
- Salva e scarica il file aggiornato.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati di metadati supportati" subTitle="Con Python puoi gestire anche i metadati di altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
