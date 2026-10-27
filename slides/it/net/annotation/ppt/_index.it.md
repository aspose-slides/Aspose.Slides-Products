---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Rimuovere le annotazioni da PPT con .NET
url: /it/net/annotation/ppt/ 
description: Rimuovi commenti e autori dei commenti dalle presentazioni PPT in C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rimuovere commenti e autori dei commenti da PPT in C#" h2="Crea applicazioni .NET che gestiscono commenti e autori nei file di presentazione con API lato server." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere i commenti da PPT tramite C#" variant="code" %}}

Usa [Aspose.Slides for .NET](/slides/it/net/) per rimuovere commenti e autori dei commenti dai file di presentazione PPT. L'esempio seguente svuota la raccolta `Comments` di ogni autore e poi la raccolta `CommentAuthors` della presentazione.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eliminare le annotazioni da PPT – C#" >}}
```cs
using var presentation = new Presentation("example.ppt");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere i commenti da PPT tramite C#" intro="Segui questi passaggi per rimuovere commenti e autori dei commenti da una presentazione PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa Aspose.Slides for .NET. Vedi [Installazione](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPT con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri la raccolta `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Svuota la raccolta `Comments` di ogni autore dei commenti.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Svuota la raccolta `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione aggiornata con `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Realizzato con Aspose.Slides" title="Rimuovere i commenti da PPT online" description="L'app gratuita Aspose.Slides Annotation è realizzata con [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPT." button="Apri Aspose.Slides Annotation" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove i commenti prima di scrivere codice.
- Rimuovi tutti i commenti dal tuo file PPT.
- Scarica il file ripulito.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per le annotazioni" subTitle="Con C#, puoi rimuovere le annotazioni anche da altri formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
