---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 360
title: Rimuovere le annotazioni da PPTX con Java
url: /it/java/annotation/pptx/ 
description: Rimuovi commenti e autori dei commenti dalle presentazioni PPTX in Java con Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rimuovere commenti e autori dei commenti da PPTX in Java" h2="Usa Aspose.Slides for Java per rimuovere commenti e autori dei commenti dai file di presentazione." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere i commenti da PPTX tramite Java" variant="code" %}}

Aspose.Slides for Java ti permette di rimuovere commenti e autori dei commenti dalle presentazioni PPTX. Carica un file con la classe `Presentation`, scorri gli oggetti `ICommentAuthor` di `getCommentAuthors`, cancella i loro commenti e salva la presentazione aggiornata.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eliminare le annotazioni da PPTX – Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere i commenti da PPTX tramite Java" intro="Segui questi passaggi per rimuovere commenti e autori dei commenti da una presentazione PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa Aspose.Slides for Java. Vedi [Installazione](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPTX con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri gli oggetti `ICommentAuthor` di `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cancella i commenti di ogni autore con `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Svuota la raccolta degli autori dei commenti e salva il file PPTX aggiornato.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Realizzato con Aspose.Slides" title="Rimuovere i commenti da PPTX online" description="L'app gratuita Aspose.Slides Annotation è realizzata con [Aspose.Slides for Java](https://products.aspose.com/slides/it/java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Annotation" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove i commenti prima di scrivere codice.
- Rimuovi tutti i commenti dal tuo file PPTX.
- Scarica il file ripulito.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per le annotazioni" subTitle="Con Java, puoi rimuovere le annotazioni anche da altri formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
