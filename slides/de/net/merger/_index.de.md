---
title: PDF, PPT, PPTX und viele andere Dateiformate mit C# zusammenführen
url: /de/net/merger/
keywords: Zusammenführen, Verbinden, PowerPoint, Präsentation, C#, .NET, Aspose
description: Führen Sie mehrere Dateien in C# PPT, PPTX, ODP, PDF, PNG, JPG und vielen mehr zusammen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Powerpoint, PDF, PPT oder andere Dokumente in C# zusammenführen" h2="Hochgeschwindigkeits-C#-Bibliothek zum Zusammenführen von PPT, PPTX, PDF, PNG, JPEG und anderen Formaten." >}}

{{% blocks/products/pf/feature-page-section h2="PPT, PPTX, PDF mit C# zusammenführen" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) ist eine leistungsstarke C#-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, mehrere PPT/PPTX-Präsentationen zu kombinieren. Wenn Sie eine Präsentation mit einer anderen zusammenführen, kombinieren Sie deren Folien effektiv in einer einzigen Präsentation, um eine Datei zu erhalten. Mit Aspose.Slides können Sie zwei Präsentationen auf unterschiedliche Weise zusammenführen. Sie können Präsentationen mit all ihren Formen, Stilen, Texten, Formatierungen, Kommentaren, Animationen usw. zusammenführen, ohne sich um Qualitäts- oder Datenverluste sorgen zu müssen.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint-Präsentationen in C# zusammenführen" %}}
Um die PowerPoint-Präsentationen zusammenzuführen, müssen Sie die Folien von einer Präsentation zur anderen klonen.

{{% blocks/products/pf/agp/code-block title="PPTX-Dateien mit C# zusammenführen" offSpacer="true" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Präsentationen mit Folienmaster mit C# zusammenführen" %}}
Dieser C#-Code zeigt, wie Sie mehrere Präsentationen zu einer zusammenführen und Stile aus der Folienmaster-Präsentationsvorlage anwenden. Die Ergebnispräsentation behält also die gleiche Quellformatierung bei und enthält die Formatierung der Masterfolie einer anderen Präsentation.

{{% blocks/products/pf/agp/code-block title="Mehrere PPT in C# zu einer zusammenführen" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="So führen Sie Präsentationen mit Aspose.Slides für die .NET-API zusammen" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte, um zwei PPTX-Dateien zusammenzuführen und das Ergebnis als PDF in .NET zu speichern." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem C#-Projekt einen Bibliotheksverweis hinzu (Importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die PPTX-Quelldateien in C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinieren Sie PPTX-Dateien mit der **AddClone**-Methode.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Präsentation speichern und Ergebnis als einzelne PDF-Datei erhalten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate zum Zusammenführen" subTitle="Sie können auch andere Dateiformate kombinieren. Weitere unterstützte Formate finden Sie weiter unten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}