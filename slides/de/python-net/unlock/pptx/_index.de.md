---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-Präsentationen mit Python entsperren
url: /de/python-net/unlock/pptx/
description: Entfernen Sie Verschlüsselung und Schreibschutz von PPTX-Präsentationen mit Python.
keywords: PPTX entsperren, Kennwort von PPTX entfernen, PPTX-Verschlüsselung entfernen, Schreibschutz von PPTX entfernen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-Präsentationen mit Python entsperren" h2="Entwickeln Sie Python-Anwendungen, die mit Aspose.Slides Öffnungskennwörter und Schreibschutzeinstellungen von PPTX-Präsentationen entfernen." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Verschlüsselung und Schreibschutz von PPTX mit Python entfernen" variant="code" %}}

Mit [Aspose.Slides for Python via .NET](/slides/de/python-net/) entfernen Sie die Verschlüsselung, die ein Kennwort zum Öffnen einer PPTX-Präsentation erfordert, oder heben deren Schreibschutz auf. Um eine verschlüsselte Datei zu öffnen, geben Sie das aktuelle Kennwort über `LoadOptions` an.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Verschlüsselung von einer PPTX-Präsentation entfernen – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz von einer PPTX-Präsentation entfernen – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie den Schutz von PPTX mit Python" intro="Gehen Sie wie folgt vor, um den Schutz von einer PPTX-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Legen Sie bei einer verschlüsselten PPTX-Datei das aktuelle Kennwort in `LoadOptions` fest und öffnen Sie die Datei dann mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `ProtectionManager.remove_encryption` auf, um das Öffnungskennwort zu entfernen, oder `ProtectionManager.remove_write_protection`, um den Schreibschutz aufzuheben.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die resultierende Präsentation mit `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online entsperren" description="Die kostenlose App Aspose.Slides Unlock basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Unlock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides den Schutz entfernt, bevor Sie Code schreiben.
- Entfernen Sie das Kennwort oder den Schreibschutz aus Ihrer PPTX-Datei.
- Laden Sie die entsperrte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Entsperren" subTitle="Entfernen Sie mit Python den Schutz auch von anderen unterstützten Präsentationsformaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
