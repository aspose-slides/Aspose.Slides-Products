---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cercare testo nelle presentazioni PPTX con Python
url: /it/python-net/search/pptx/
description: Cerca testo nelle presentazioni PPTX con Python e Aspose.Slides.
keywords: cercare testo in PPTX, trovare parole in PPTX, cercare nella presentazione PPTX con Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cercare testo nelle presentazioni PPTX con Python" h2="Crea applicazioni Python che trovano testo nelle presentazioni PowerPoint con Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cercare testo in una presentazione PPTX con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/it/python-net/), puoi usare [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) per trovare in ogni diapositiva le cornici di testo che contengono una determinata stringa.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cercare testo in una presentazione PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come cercare testo in PPTX con Python" intro="Segui questi passaggi per cercare testo in una presentazione PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri il file PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri le diapositive e chiama [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) per ciascuna.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leggi la proprietà `text` di ogni cornice di testo trovata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Realizzato con Aspose.Slides" title="Cercare testo nei file PPTX online" description="L'app gratuita Aspose.Slides Search è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Search" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides trova il testo prima di scrivere codice.
- Cerca testo semplice o espressioni regolari nel tuo file PPTX.
- Scarica le corrispondenze come file di testo.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la ricerca" subTitle="Usa Python per cercare testo in altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
