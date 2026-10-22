---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Modifica PPT in Java
url: /it/java/editor/ppt/
keywords: Modifica PPT, modifica PowerPoint, PPT, PowerPoint, API Java, libreria Java
description: Modifica PPT in Java. Usa l'API della libreria Java per modificare la presentazione di PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifica PPT in Java" h2="Libreria Java ad alta velocità e multipiattaforma per la modifica di PPT utilizzando il codice Java" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifica PPT in Java" variant="code" %}}

Utilizzando [**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/), puoi aggiungere una nuova riga di testo a un documento PPT con poche righe di codice.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice Java per la modifica di PPT" >}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifica PPT utilizzando Aspose.Slides" %}}

[**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/) è una potente libreria Java utilizzata per manipolare e modificare le presentazioni. Puoi modificare una presentazione PPT aggiungendovi una nuova riga di testo.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come modificare PPT in Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa **Aspose.Slides per Java**. Vedi [**Installazione**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi la libreria come riferimento nel tuo progetto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un'istanza della classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica la presentazione PPT che desideri modificare.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi una nuova riga di testo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file PowerPoint modificato.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Modifica altri file" subTitle="Puoi anche modificare i file in altri formati" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
