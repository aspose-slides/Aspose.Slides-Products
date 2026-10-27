---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Kommentare aus ODP in Python entfernen
url: /de/python-net/annotation/odp/ 
description: Entfernen Sie Kommentare und Kommentarautoren aus ODP-Präsentationen in Python mit Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Kommentare und Kommentarautoren aus ODP in Python entfernen" h2="Entfernen Sie mit Aspose.Slides for Python via .NET Präsentationskommentare und die zugehörigen Autoren." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Kommentare aus ODP mit Python entfernen" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/de/python-net/) bietet Zugriff auf die Kommentare und Kommentarautoren einer ODP-Präsentation. Laden Sie die Datei mit `Presentation`, leeren Sie die `comments`-Sammlung jedes Autors und `comment_authors` und speichern Sie das Ergebnis im ODP-Format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kommentare aus ODP in Python entfernen" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie Kommentare aus ODP mit Python" intro="Gehen Sie wie folgt vor, um alle Kommentare und Kommentarautoren aus einer ODP-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die ODP-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie `comment_authors` und leeren Sie die `comments`-Sammlung jedes Autors.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leeren Sie die Sammlung `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `save` mit `SaveFormat.ODP` auf, um die aktualisierte ODP-Präsentation zu schreiben.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Entwickelt mit Aspose.Slides" title="ODP-Kommentare online entfernen" description="Die kostenlose App Aspose.Slides Annotation basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Annotation öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Kommentare entfernt, bevor Sie Code schreiben.
- Entfernen Sie alle Kommentare aus Ihrer ODP-Datei.
- Laden Sie die bereinigte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Anmerkungen" subTitle="Mit Python können Sie Anmerkungen auch aus anderen Formaten entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
