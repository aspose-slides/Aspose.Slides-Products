---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Oscurare testo nelle presentazioni ODP con Python
url: /it/python-net/redaction/odp/
description: Trova e sostituisci testo riservato nelle presentazioni ODP con Python.
keywords: oscurare ODP, trovare e sostituire testo in ODP, aggiornare presentazione ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Oscurare testo nelle presentazioni ODP con Python" h2="Crea applicazioni Python che trovano e sostituiscono testo riservato nelle presentazioni con Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Oscurare testo in una presentazione ODP con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/it/python-net/), puoi sostituire testo riservato in tutta una presentazione ODP. Usa `Presentation.replace_text` con `TextSearchOptions` per controllare la ricerca, quindi salva la presentazione modificata.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Oscurare testo in una presentazione ODP – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.odp") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come oscurare testo in una presentazione ODP con Python" intro="Segui questi passaggi per sostituire testo riservato in una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri il file ODP con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Usa [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) con `TextSearchOptions` per sostituire il testo desiderato.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione modificata con `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Realizzato con Aspose.Slides" title="Oscurare file ODP online" description="L'app gratuita Aspose.Slides Redaction è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Redaction" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides trova e sostituisce testo prima di scrivere codice.
- Trova e sostituisci testo nel tuo file ODP, anche con espressioni regolari.
- Scarica il file oscurato.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per l'oscuramento" subTitle="Usa Python per oscurare testo in altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
