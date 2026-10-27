---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Rimuovere le annotazioni da ODP con C++
url: /it/cpp/annotation/odp/ 
description: Codice sorgente C++ per rimuovere le annotazioni dalle presentazioni ODP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rimuovere commenti e autori dei commenti da ODP in C++" h2="Crea app C++ che gestiscono commenti e autori nei file di presentazione con API lato server." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere i commenti da ODP tramite C++" variant="code" %}}

Usa [Aspose.Slides for C++](/slides/it/cpp/) per rimuovere commenti e autori dei commenti dalle presentazioni ODP. L'esempio seguente cancella i commenti di ogni autore di `get_CommentAuthors` e poi svuota la raccolta degli autori dei commenti.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eliminare le annotazioni da ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.odp");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere i commenti da ODP tramite C++" intro="Segui questi passaggi per rimuovere commenti e autori dei commenti da una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa Aspose.Slides for C++. Vedi [Installazione](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file ODP con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri gli autori dei commenti di `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cancella i commenti di ogni autore con `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Svuota la raccolta degli autori dei commenti.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione aggiornata con `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Realizzato con Aspose.Slides" title="Rimuovere i commenti da ODP online" description="L'app gratuita Aspose.Slides Annotation è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Annotation" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove i commenti prima di scrivere codice.
- Rimuovi tutti i commenti dal tuo file ODP.
- Scarica il file ripulito.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per le annotazioni" subTitle="Con C++, puoi rimuovere le annotazioni anche da altri formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
