---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Rimuovere i commenti da PPT in Python
url: /it/python-net/annotation/ppt/ 
description: Rimuovi commenti e autori dei commenti dalle presentazioni PPT in Python con Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rimuovere commenti e autori dei commenti da PPT in Python" h2="Usa Aspose.Slides for Python via .NET per rimuovere i commenti di una presentazione e i relativi autori." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere i commenti da PPT tramite Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/it/python-net/) dà accesso ai commenti e agli autori dei commenti memorizzati in una presentazione PPT. Carica il file con `Presentation`, svuota la raccolta `comments` di ogni autore, svuota `comment_authors` e salva il risultato in formato PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere i commenti da PPT in Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere i commenti da PPT tramite Python" intro="Segui questi passaggi per rimuovere tutti i commenti e gli autori dei commenti da una presentazione PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri il file PPT con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri `comment_authors` e svuota la raccolta `comments` di ogni autore.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Svuota la raccolta `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `save` con `SaveFormat.PPT` per scrivere la presentazione PPT aggiornata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Realizzato con Aspose.Slides" title="Rimuovere i commenti da PPT online" description="L'app gratuita Aspose.Slides Annotation è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPT." button="Apri Aspose.Slides Annotation" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove i commenti prima di scrivere codice.
- Rimuovi tutti i commenti dal tuo file PPT.
- Scarica il file ripulito.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per le annotazioni" subTitle="Con Python, puoi rimuovere le annotazioni anche da altri formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
