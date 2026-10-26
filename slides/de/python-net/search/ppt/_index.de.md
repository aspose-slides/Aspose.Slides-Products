---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Text in PPT-Präsentationen mit Python durchsuchen
url: /de/python-net/search/ppt/
description: Suchen Sie mit Python und Aspose.Slides nach Text in PPT-Präsentationen.
keywords: Text in PPT durchsuchen, Wörter in PPT finden, PPT-Präsentation mit Python durchsuchen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Text in PPT-Präsentationen mit Python durchsuchen" h2="Entwickeln Sie Python-Anwendungen, die mit Aspose.Slides Text in PowerPoint-Präsentationen finden." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Text in einer PPT-Präsentation mit Python durchsuchen" variant="code" %}}

Mit [Aspose.Slides for Python via .NET](/slides/de/python-net/) finden Sie mit [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) die Textrahmen jeder Folie, die eine bestimmte Zeichenfolge enthalten.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Text in einer PPT-Präsentation durchsuchen – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So durchsuchen Sie Text in PPT mit Python" intro="Gehen Sie wie folgt vor, um in einer PPT-Präsentation nach Text zu suchen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die PPT-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die Folien und rufen Sie für jede [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) auf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lesen Sie die Eigenschaft `text` jedes gefundenen Textrahmens.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Entwickelt mit Aspose.Slides" title="Text in PPT-Dateien online durchsuchen" description="Die kostenlose App Aspose.Slides Search basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPT-Dateien leisten kann." button="Aspose.Slides Search öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Text findet, bevor Sie Code schreiben.
- Durchsuchen Sie Ihre PPT-Datei nach einfachem Text oder regulären Ausdrücken.
- Laden Sie die Treffer als Textdatei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für die Suche" subTitle="Suchen Sie mit Python auch in anderen unterstützten Präsentationsformaten nach Text." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
