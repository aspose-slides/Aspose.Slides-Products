---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Estrarre testo da file ODP con Python
url: /it/python-net/parser/odp/
description: Estrai testo e dettagli di formattazione del testo da presentazioni ODP con Python.
keywords: analizzare ODP con Python, parser ODP Python, estrarre dati da ODP in Python, estrarre testo da ODP con Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Estrarre testo da presentazioni ODP con Python" h2="Crea applicazioni Python che estraggono testo e dettagli di formattazione da presentazioni OpenDocument con Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Estrarre testo da una presentazione ODP con Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/it/python-net/) fornisce il metodo statico [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) di `SlideUtil`. Restituisce gli oggetti `TextFrame` dell'intera presentazione e può includere il testo delle diapositive master. L'esempio seguente estrae il testo e i relativi dettagli del carattere da una presentazione ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Estrarre testo da una presentazione ODP – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come estrarre testo da ODP con Python" intro="Segui questi passaggi per estrarre testo da un file ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri il file ODP con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `SlideUtil.get_all_text_frames` e specifica se includere le diapositive master.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri gli oggetti `TextFrame` restituiti.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri la raccolta `paragraphs` di ogni cornice di testo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri la raccolta `portions` di ogni paragrafo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leggi `text` e le proprietà di formattazione della porzione corrente.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Realizzato con Aspose.Slides" title="Estrarre testo e immagini online" description="L'app gratuita Aspose.Slides Parser è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Parser" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides legge i tuoi file prima di scrivere codice.
- Carica un file ODP e ottieni il suo testo e le sue immagini.
- Scarica tutto in un unico archivio ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati di analisi supportati" subTitle="Con Python puoi estrarre testo anche da altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
