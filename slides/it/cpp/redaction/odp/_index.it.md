---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Oscurare presentazioni ODP con C++
url: /it/cpp/redaction/odp/
description: Oscura le presentazioni ODP in C++. Usa Aspose.Slides for C++ per trovare e sostituire testo riservato nei file di presentazione.
keywords: oscurare ODP, trovare e sostituire testo in ODP, aggiornare presentazione ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Oscurare un ODP con C++" h2="Usa Aspose.Slides for C++ per trovare e sostituire testo riservato nei file di presentazione senza Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Oscurare una presentazione ODP tramite C++" variant="code" %}}

Aspose.Slides for C++ ti permette di oscurare le presentazioni ODP sostituendo il testo riservato nelle diapositive. Usa `SlideUtil::FindAndReplaceText` con un oggetto `Presentation` per cercare nella presentazione e sostituire il testo corrispondente prima di salvare il file aggiornato.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Oscurare una presentazione ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come oscurare un ODP tramite C++" intro="Segui questi passaggi per oscurare una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file ODP con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Usa il metodo [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) per trovare e sostituire il testo riservato.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file oscurato con `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Realizzato con Aspose.Slides" title="Oscurare file ODP online" description="L'app gratuita Aspose.Slides Redaction è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Redaction" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides trova e sostituisce testo prima di scrivere codice.
- Trova e sostituisci testo nel tuo file ODP, anche con espressioni regolari.
- Scarica il file oscurato.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per l'oscuramento" subTitle="Con C++, puoi oscurare anche i seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
