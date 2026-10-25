---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Text aus PPTX-Dateien mit Python extrahieren
url: /de/python-net/parser/pptx/
description: Text und Textformatierungsdetails aus PPTX-Präsentationen mit Python extrahieren.
keywords: PPTX mit Python parsen, PPTX-Parser Python, Daten aus PPTX in Python extrahieren, Text aus PPTX mit Python extrahieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Text aus PPTX-Präsentationen mit Python extrahieren" h2="Entwickeln Sie Python-Anwendungen, die mit Aspose.Slides Text und Details zur Textformatierung aus PowerPoint-Präsentationen extrahieren." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Text aus einer PPTX-Präsentation mit Python extrahieren" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/de/python-net/) bietet die statische Methode [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) der Klasse `SlideUtil`. Sie gibt die `TextFrame`-Objekte der gesamten Präsentation zurück und kann auch Text aus Masterfolien einbeziehen. Das folgende Beispiel extrahiert Text und zugehörige Schriftdetails aus einer PPTX-Präsentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Text aus einer PPTX-Präsentation extrahieren – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So extrahieren Sie Text aus PPTX mit Python" intro="Gehen Sie wie folgt vor, um Text aus einer PPTX-Datei zu extrahieren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die PPTX-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `SlideUtil.get_all_text_frames` auf und legen Sie fest, ob Masterfolien einbezogen werden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die zurückgegebenen `TextFrame`-Objekte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die Sammlung `paragraphs` jedes Textrahmens.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die Sammlung `portions` jedes Absatzes.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lesen Sie `text` und die Formatierungseigenschaften des aktuellen Textabschnitts.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Entwickelt mit Aspose.Slides" title="Text und Bilder online extrahieren" description="Die kostenlose App Aspose.Slides Parser basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Parser öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Ihre Dateien liest, bevor Sie Code schreiben.
- Laden Sie eine PPTX-Datei hoch und erhalten Sie ihren Text und ihre Bilder.
- Laden Sie alles als ein ZIP-Archiv herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Parsen" subTitle="Mit Python können Sie auch Text aus anderen unterstützten Präsentationsformaten extrahieren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
