---
title: Oscura i file di presentazione ODP utilizzando Java
url: /it/java/redaction/odp/
keywords: Oscura ODP, trova e sostituisci testo in ODP, aggiorna ODP Presentazione
description: Java codice sorgente per trovare e sostituire il testo nella presentazione ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Oscura ODP utilizzando Java" h2="Crea le tue app Java per trovare e sostituire il testo nei file di presentazione utilizzando le API lato server. Scopri come cercare e sostituire il testo nei contenuti, nei commenti o nei metadati delle presentazioni ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Oscura presentazione ODP tramite Java" %}}
Una ricerca di documenti di base e la sostituzione del testo nei contenuti, nei commenti, nelle note delle diapositive o nei metadati con le API di Aspose.Slides for Java possono essere eseguite con poche righe di codice. Trova e sostituisci il testo in PowerPoint e OpenOffice. Modifica testo, commenti, metadati nella presentazione tramite la corrispondenza dei dati regexp.
{{% blocks/products/pf/agp/code-block title="Oscura presentazione ODP utilizzando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come redigere ODP tramite Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per oscurare i file ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica ODP con un'istanza di Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilizza il metodo [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) per trovare e sostituire il testo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redazione Live Demo" sectionDescription="Cerca e sostituisci subito il testo nei contenuti, nei commenti o nei metadati nei documenti ODP." >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati Redact supportati" subTitle="Utilizzando Java, puoi anche oscurare i seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}