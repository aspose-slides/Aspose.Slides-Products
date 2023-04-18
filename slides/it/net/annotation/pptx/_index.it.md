---
title: Rimuovi l'annotazione PPTX utilizzando .NET
weight: 4380
url: /it/net/annotation/pptx/ 
description: Codice sorgente C# per eliminare le annotazioni in formato PPTX su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Rimuovi commenti e autori di commenti da PPTX in C#" h2="Crea le tue app .NET per manipolare commenti e autori nei file di documenti utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Rimuovi commenti da PPTX tramite C#" %}}
Per rimuovere le annotazioni dal file PPTX, utilizzeremo l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net) che è ricca di funzionalità, potente e facile da usare API di manipolazione dei documenti per la piattaforma C#.
{{% blocks/products/pf/agp/code-block title="Elimina annotazioni da PPTX - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Come rimuovere i commenti da PPTX tramite C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa **Aspose.Slides per .NET**. Vedere [**Installazione**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPTX con un'istanza della classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Itera su tutti gli autori del PPTX caricato
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rimuovi tutti i commenti di un autore
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rimuovi tutti gli autori alla fine
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di annotazione supportati" subTitle="Usando C#, si possono facilmente annotare altri formati inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}