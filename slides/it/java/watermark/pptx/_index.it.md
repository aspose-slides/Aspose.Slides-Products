---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Aggiungere una filigrana a file di presentazione PPTX con Java
url: /it/java/watermark/pptx/
description: Aggiungi filigrane di testo e immagine a presentazioni PPTX in Java con Aspose.Slides for Java.
keywords: aggiungere filigrana a PPTX, aggiungere filigrana di testo a PPTX, aggiungere filigrana immagine a PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Aggiungere una filigrana a una presentazione PPTX con Java" h2="Crea applicazioni Java che inseriscono filigrane di testo o immagine nei file di presentazione con API lato server." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aggiungere una filigrana a una presentazione PPTX tramite Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/it/java/) puoi aggiungere filigrane di testo e immagine alle presentazioni PPTX. Aggiungi una forma di filigrana a una diapositiva master, così la filigrana compare nelle diapositive che usano quel master.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere una filigrana di testo a PPTX con Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere una filigrana immagine a una presentazione PPTX con Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come aggiungere una filigrana a PPTX con Java" intro="Segui questi passaggi per aggiungere una filigrana di testo o immagine ai file PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file `PPTX` con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Seleziona una diapositiva master con il metodo `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `addAutoShape` per aggiungere una forma di filigrana.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `addTextFrame` per aggiungere il testo della filigrana oppure usa `addImage` per una filigrana immagine.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione con filigrana in formato PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Realizzato con Aspose.Slides" title="Aggiungi filigrane a file PPTX online" description="L'app gratuita Aspose.Slides Watermark è realizzata con [Aspose.Slides for Java](https://products.aspose.com/slides/it/java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Watermark" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides aggiunge le filigrane prima di scrivere codice.
- Aggiungi una filigrana di testo o immagine al tuo file PPTX.
- Scarica il file con filigrana.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per le filigrane" subTitle="Con Java puoi aggiungere filigrane anche ai seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
