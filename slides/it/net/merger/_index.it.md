---
title: Unisci PDF, PPT, PPTX e molti altri formati di file usando C#
url: /it/net/merger/
keywords: Unisci, Unisci, PowerPoint, Presentazione, C#, .NET, Aspose
description: Unisci più file in C# PPT, PPTX, ODP, PDF, PNG, JPG e molti altri.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Unisci Powerpoint, PDF, PPT o altri documenti insieme in C#" h2="Libreria C# ad alta velocità per unire PPT, PPTX, PDF, PNG, JPEG e altri formati." >}}

{{% blocks/products/pf/feature-page-section h2="Unisci PPT, PPTX, PDF usando C#" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/it/net/) è una potente libreria C# per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per combinare più presentazioni PPT/PPTX. Quando unisci una presentazione a un'altra, combini efficacemente le loro diapositive in un'unica presentazione per ottenere un file. Aspose.Slides ti consente di unire due presentazioni in modi diversi. Puoi unire le presentazioni con tutte le loro forme, stili, testi, formattazione, commenti, animazioni, ecc. senza doversi preoccupare della perdita di qualità o dati.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Unisci presentazioni PowerPoint in C#" %}}
Per unire le presentazioni PowerPoint, dovrai clonare le diapositive da una presentazione all'altra.

{{% blocks/products/pf/agp/code-block title="Unisci file PPTX usando C#" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Unisci presentazioni con Slide Master usando C#" %}}
Questo codice C# mostra come unire più presentazioni in una e applicare stili dal modello di presentazione dello schema diapositiva. Pertanto, la presentazione dei risultati manterrà la stessa formattazione di origine e conterrà la formattazione dalla diapositiva master di un'altra presentazione.

{{% blocks/products/pf/agp/code-block title="Unisci più PPT in un singolo in C#" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come unire le presentazioni usando Aspose.Slides per .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per unire due file PPTX e salvare il risultato come PDF in .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file PPTX di origine in C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combina i file PPTX usando il metodo **AddClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva la presentazione e ottieni il risultato come singolo file PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati supportati da unire" subTitle="Puoi anche combinare altri formati di file. Vedi altri formati supportati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}