---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Text in PPT-Präsentationen mit Python schwärzen
url: /de/python-net/redaction/ppt/
description: Suchen und ersetzen Sie vertraulichen Text in PPT-Präsentationen mit Python.
keywords: PPT schwärzen, Text in PPT suchen und ersetzen, PPT-Präsentation aktualisieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Text in PPT-Präsentationen mit Python schwärzen" h2="Entwickeln Sie Python-Anwendungen, die mit Aspose.Slides vertraulichen Text in Präsentationen suchen und ersetzen." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Text in einer PPT-Präsentation mit Python schwärzen" variant="code" %}}

Mit [Aspose.Slides for Python via .NET](/slides/de/python-net/) ersetzen Sie vertraulichen Text in der gesamten PPT-Präsentation. Steuern Sie die Suche mit `Presentation.replace_text` und `TextSearchOptions` und speichern Sie anschließend die geänderte Präsentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Text in einer PPT-Präsentation schwärzen – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schwärzen Sie Text in einer PPT-Präsentation mit Python" intro="Gehen Sie wie folgt vor, um vertraulichen Text in einer PPT-Präsentation zu ersetzen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die PPT-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ersetzen Sie den gewünschten Text mit [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) und `TextSearchOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geänderte Präsentation mit `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Entwickelt mit Aspose.Slides" title="PPT-Dateien online schwärzen" description="Die kostenlose App Aspose.Slides Redaction basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPT-Dateien leisten kann." button="Aspose.Slides Redaction öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Text sucht und ersetzt, bevor Sie Code schreiben.
- Suchen und ersetzen Sie Text in Ihrer PPT-Datei, auch mit regulären Ausdrücken.
- Laden Sie die geschwärzte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Schwärzen" subTitle="Schwärzen Sie mit Python auch Text in anderen unterstützten Präsentationsformaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
