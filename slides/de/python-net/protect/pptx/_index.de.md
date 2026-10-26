---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-Präsentationsdateien mit Python schützen
url: /de/python-net/protect/pptx/
description: Verschlüsseln Sie PPTX-Präsentationen oder legen Sie mit Python einen Schreibschutz fest.
keywords: PPTX-Schreibschutz, PPTX mit Python verschlüsseln, PPTX-Präsentation sperren, PPTX mit Python schützen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-Präsentationen mit Python schützen" h2="Entwickeln Sie Python-Anwendungen, die Präsentationen mit Aspose.Slides verschlüsseln oder schreibschützen." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine PPTX-Präsentation mit Python schützen" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/de/python-net/) bietet zwei unterschiedliche Schutzmechanismen. Rufen Sie `ProtectionManager.encrypt` auf, um eine PPTX-Präsentation zu verschlüsseln, sodass sie sich nur mit einem Kennwort öffnen lässt. Alternativ rufen Sie `ProtectionManager.set_write_protection` auf, um von Änderungen abzuhalten, ohne die Datei zu verschlüsseln. Eine schreibgeschützte Präsentation lässt sich weiterhin öffnen und Änderungen können in einer anderen Datei gespeichert werden.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine PPTX-Präsentation verschlüsseln – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz für eine PPTX-Präsentation festlegen – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schützen Sie PPTX mit Python" intro="Gehen Sie wie folgt vor, um eine PPTX-Datei zu schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die PPTX-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Verwenden Sie `ProtectionManager.encrypt`, um ein Kennwort zum Öffnen vorauszusetzen, oder `ProtectionManager.set_write_protection`, um von Änderungen abzuhalten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geschützte Präsentation mit `SaveFormat.PPTX` als PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online mit einem Kennwort schützen" description="Die kostenlose App Aspose.Slides Lock basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Lock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Präsentationen schützt, bevor Sie Code schreiben.
- Legen Sie ein Kennwort zum Öffnen oder Bearbeiten Ihrer PPTX-Datei fest.
- Laden Sie die geschützte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für den Schutz" subTitle="Schützen Sie mit Python auch andere unterstützte Präsentationsformate." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
