---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cercare testo nelle presentazioni ODP con C++
url: /it/cpp/search/odp/
description: Cerca testo nelle presentazioni ODP in C++. Usa Aspose.Slides for C++ per trovare testo nei file di presentazione.
keywords: cercare parole in ODP, trovare testo in ODP, cercare testo nella presentazione ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cercare testo in ODP con C++" h2="Usa Aspose.Slides for C++ per trovare testo nei file di presentazione senza Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cercare testo in una presentazione ODP tramite C++" variant="code" %}}

Aspose.Slides for C++ ti permette di cercare testo nelle presentazioni ODP. Usa `SlideUtil::GetAllTextBoxes` per raccogliere le cornici di testo di una diapositiva, quindi controlla se il loro testo contiene la frase richiesta.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cercare testo in una presentazione ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come cercare testo in ODP tramite C++" intro="Segui questi passaggi per cercare testo in una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file ODP con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ottieni la diapositiva richiesta con `Presentation::get_Slides` e recupera le sue cornici di testo con [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Controlla se il testo di ogni cornice contiene la frase richiesta.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Realizzato con Aspose.Slides" title="Cercare testo nei file ODP online" description="L'app gratuita Aspose.Slides Search è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Search" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides trova il testo prima di scrivere codice.
- Cerca testo semplice o espressioni regolari nel tuo file ODP.
- Scarica le corrispondenze come file di testo.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la ricerca" subTitle="Con C++, puoi cercare testo anche nei seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
