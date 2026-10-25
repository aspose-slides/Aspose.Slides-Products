---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Visualizzare o modificare i metadati di file PPSM con Java
url: /it/java/metadata/ppsm/
description: Visualizza e modifica i metadati PPSM in Java. Usa Aspose.Slides for Java per aggiornare le proprietà predefinite e personalizzate delle presentazioni.
keywords: Modificare metadati PPSM, visualizzare metadati PPSM, modificare proprietà PPSM, visualizzare proprietà PPSM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modificare le proprietà PPSM con Java" h2="Crea applicazioni Java che modificano le proprietà predefinite e personalizzate dei file di presentazione con API lato server." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modificare le proprietà PPSM tramite Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/it/java/) gli sviluppatori possono accedere alle proprietà predefinite e personalizzate di una presentazione e modificarle. Usa il metodo `getDocumentProperties` di un oggetto `Presentation` per accedere all'oggetto `IDocumentProperties` del file di presentazione.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Modificare le proprietà predefinite di PPSM – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.ppsm");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.ppsm", SaveFormat.Ppsm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere proprietà personalizzate a PPSM – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.ppsm", SaveFormat.Ppsm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come visualizzare o modificare i metadati PPSM in Java" intro="Segui questi passaggi per visualizzare o modificare i metadati PPSM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file `PPSM` con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `getDocumentProperties` per ottenere l'oggetto `IDocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leggi o aggiorna proprietà predefinite come `Author`, `Title`, `Subject` e `Comments`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Accedi alle proprietà personalizzate e modificale con `set_Item`, `getCustomPropertyName` e `removeCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Realizzato con Aspose.Slides" title="Visualizzare e modificare i metadati PPSM online" description="L'app gratuita Aspose.Slides Metadata è realizzata con [Aspose.Slides for Java](https://products.aspose.com/slides/it/java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPSM." button="Apri Aspose.Slides Metadata" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides legge e scrive le proprietà prima di scrivere codice.
- Visualizza e modifica le proprietà predefinite e personalizzate del tuo file PPSM.
- Salva e scarica il file aggiornato.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati di metadati supportati" subTitle="Con Java puoi gestire anche i metadati dei seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
