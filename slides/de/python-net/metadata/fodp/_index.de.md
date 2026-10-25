---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: FODP-Metadaten mit Python anzeigen oder bearbeiten
url: /de/python-net/metadata/fodp/
description: Integrierte und benutzerdefinierte Metadateneigenschaften in FODP-Dateien mit Python anzeigen und bearbeiten.
keywords: FODP-Metadaten bearbeiten, FODP-Metadaten anzeigen, FODP-Eigenschaften bearbeiten, FODP-Eigenschaften anzeigen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="FODP-Metadaten mit Python anzeigen und bearbeiten" h2="Entwickeln Sie Python-Anwendungen, die mit Aspose.Slides integrierte und benutzerdefinierte Präsentationseigenschaften lesen und ändern." related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="FODP-Metadaten mit Python anzeigen und ändern" variant="code" %}}

Mit [**Aspose.Slides for Python via .NET**](/slides/de/python-net/) lesen und aktualisieren Sie integrierte Metadaten und fügen benutzerdefinierte Dokumenteigenschaften in FODP-Präsentationen hinzu, aktualisieren oder entfernen sie. Greifen Sie über `Presentation.document_properties` auf ein [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/)-Objekt zu, ändern Sie es und speichern Sie die Präsentation im FODP-Format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Integrierte FODP-Eigenschaften aktualisieren – Python" >}}
```python
with slides.Presentation("presentation.fodp") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.fodp", slides.export.SaveFormat.FODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Benutzerdefinierte FODP-Eigenschaften hinzufügen und entfernen – Python" >}}
```python
with slides.Presentation("presentation.fodp") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.fodp", slides.export.SaveFormat.FODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So bearbeiten Sie FODP-Metadaten mit Python" intro="Gehen Sie wie folgt vor, um die Metadaten einer FODP-Datei zu bearbeiten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die FODP-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Greifen Sie über `Presentation.document_properties` auf das `IDocumentProperties`-Objekt zu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aktualisieren Sie integrierte Eigenschaften oder verwenden Sie `set_custom_property_value` und `remove_custom_property` für benutzerdefinierte Eigenschaften.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die Präsentation mit `Presentation.save` und `SaveFormat.FODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Entwickelt mit Aspose.Slides" title="FODP-Metadaten online anzeigen und bearbeiten" description="Die kostenlose App Aspose.Slides Metadata basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen FODP-Dateien leisten kann." button="Aspose.Slides Metadata öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Eigenschaften liest und schreibt, bevor Sie Code schreiben.
- Zeigen Sie integrierte und benutzerdefinierte Eigenschaften Ihrer FODP-Datei an und bearbeiten Sie sie.
- Speichern Sie die aktualisierte Datei und laden Sie sie herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Metadatenformate" subTitle="Mit Python können Sie auch die Metadaten anderer unterstützter Präsentationsformate bearbeiten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
