---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cercare testo nei file di presentazione PPT con Java
url: /it/java/search/ppt/
description: Cerca testo nelle presentazioni PPT in Java con Aspose.Slides for Java.
keywords: cercare parole in PPT, cercare testo in PPT, cercare testo nella presentazione PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cercare testo in PPT con Java" h2="Crea applicazioni Java che cercano testo nei file di presentazione con API lato server." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cercare testo in una presentazione PPT tramite Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/it/java/), puoi cercare testo nelle presentazioni PPT. Usa il metodo `SlideUtil.getAllTextBoxes` per raccogliere le cornici di testo e poi esamina gli oggetti `ITextFrame`, `IParagraph` e `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cercare testo in una presentazione PPT con Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come cercare testo in PPT tramite Java" intro="Segui questi passaggi per cercare testo in una presentazione PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPT con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `SlideUtil.getAllTextBoxes` per raccogliere le cornici di testo di ogni diapositiva.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Esamina gli oggetti `ITextFrame`, `IParagraph` e `IPortion` per trovare il testo corrispondente.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Realizzato con Aspose.Slides" title="Cercare testo nei file PPT online" description="L'app gratuita Aspose.Slides Search è realizzata con [Aspose.Slides for Java](https://products.aspose.com/slides/it/java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPT." button="Apri Aspose.Slides Search" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides trova il testo prima di scrivere codice.
- Cerca testo semplice o espressioni regolari nel tuo file PPT.
- Scarica le corrispondenze come file di testo.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la ricerca" subTitle="Con Java, puoi cercare testo anche nei seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
