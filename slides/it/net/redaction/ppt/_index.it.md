---
title: Oscura i file di presentazione PPT utilizzando .NET
url: /it/net/redaction/ppt/
keywords: Oscura PPT, trova e sostituisci testo in PPT, aggiorna PPT Presentazione
description: C# codice sorgente per trovare e sostituire il testo nella presentazione PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Oscura PPT utilizzando C#" h2="Crea le tue app .NET per trovare e sostituire il testo nei file di presentazione utilizzando le API lato server. Scopri come cercare e sostituire il testo nei contenuti, nei commenti o nei metadati delle presentazioni PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Oscura presentazione PPT tramite C#" %}}
Una ricerca di documenti di base e la sostituzione del testo nei contenuti, nei commenti, nelle note delle diapositive o nei metadati con le API di Aspose.Slides for .NET possono essere eseguite con poche righe di codice. Trova e sostituisci il testo in PowerPoint e OpenOffice. Modifica testo, commenti, metadati nella presentazione tramite la corrispondenza dei dati regexp.
{{% blocks/products/pf/agp/code-block title="Oscura presentazione PPT utilizzando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come redigere PPT tramite C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per oscurare i file PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPT con un'istanza di Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilizza il metodo [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) per trovare e sostituire il testo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Redazione Live Demo" sectionDescription="Cerca e sostituisci subito il testo nei contenuti, nei commenti o nei metadati nei documenti PPT." >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati Redact supportati" subTitle="Utilizzando C#, puoi anche oscurare i seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}