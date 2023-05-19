---
title: Cerca testo nei file di presentazione PPTX utilizzando .NET
url: /it/net/search/pptx/
keywords: cerca parole in PPTX, cerca e sostituisci testo in PPTX, cerca testo PPTX Presentazione
description: C# codice sorgente per cercare testo nella presentazione PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Cerca testo PPTX utilizzando C#" h2="Crea le tue app .NET per cercare e sostituire il testo nei file di presentazione utilizzando le API lato server. Scopri come trovare tutte le entrate di una determinata parola o frase nei documenti di presentazione. Cerca il testo in base alla corrispondenza esatta dei dati e alla corrispondenza delle espressioni regolari." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Cerca e sostituisci testo PPTX Presentazione tramite C#" %}}
Una ricerca di documenti di base e la sostituzione del testo nei contenuti, nei commenti, nelle note delle diapositive o nei metadati con le API di Aspose.Slides for .NET possono essere eseguite con poche righe di codice. Usa la corrispondenza delle espressioni regolari, abbina maiuscole e minuscole per cercare il testo nella presentazione. Cerca testo in titoli, contenuto, piè di pagina o intestazione.
{{% blocks/products/pf/agp/code-block title="Cerca testo PPTX Presentazione utilizzando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.pptx"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come cercare testo in PPTX tramite C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per cercare file di testo PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPTX con un'istanza di Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilizza il metodo [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) per trovare e sostituire il testo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Cerca demo dal vivo" sectionDescription="Cerca e sostituisci subito il testo nei contenuti, nei commenti o nei metadati nei documenti PPTX." >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di ricerca supportati" subTitle="Utilizzando C#, puoi anche cercare testo nei seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}