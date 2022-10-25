---
title: Voeg PDF, PPT, PPTX en vele andere bestandsindelingen samen met C#
url: /nl/net/merger/
keywords: Samenvoegen, Deelnemen, PowerPoint, Presentatie, C#, .NET, Aspose
description: Voeg meerdere bestanden samen in C# PPT, PPTX, ODP, PDF, PNG, JPG en nog veel meer.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Voeg Powerpoint, PDF, PPT of andere documenten samen in C#" h2="High-speed C#-bibliotheek om PPT, PPTX, PDF, PNG, JPEG en andere formaten samen te voegen." >}}

{{% blocks/products/pf/feature-page-section h2="PPT, PPTX, PDF samenvoegen met C#" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/nl/net/) is een krachtige C#-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om meerdere PPT/PPTX-presentaties te combineren. Wanneer u de ene presentatie met de andere samenvoegt, combineert u effectief hun dia's in één presentatie om één bestand te verkrijgen. Met Aspose.Slides kunt u twee presentaties op verschillende manieren samenvoegen. U kunt presentaties samenvoegen met al hun vormen, stijlen, teksten, opmaak, opmerkingen, animaties, enz. zonder dat u zich zorgen hoeft te maken over kwaliteitsverlies of gegevens.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint-presentaties samenvoegen in C#" %}}
Om de PowerPoint-presentaties samen te voegen, moet u de dia's van de ene presentatie naar de andere klonen.

{{% blocks/products/pf/agp/code-block title="Voeg PPTX-bestanden samen met C#" offSpacer="true" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Presentaties samenvoegen met Slide Master met C#" %}}
Deze C#-code laat zien hoe u verschillende presentaties kunt samenvoegen tot één en stijlen kunt toepassen vanuit een diamodel-presentatiesjabloon. De resultaatpresentatie behoudt dus dezelfde bronopmaak en bevat opmaak van de basisdia van een andere presentatie.

{{% blocks/products/pf/agp/code-block title="Voeg meerdere PPT's samen tot één in C#" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Presentaties samenvoegen met Aspose.Slides voor .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om twee PPTX-bestanden samen te voegen en het resultaat op te slaan als PDF in .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw C#-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bron-PPTX-bestanden in C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combineer PPTX-bestanden met de **AddClone**-methode.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla de presentatie op en krijg het resultaat als één PDF-bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde indelingen om samen te voegen" subTitle="U kunt ook andere bestandsindelingen combineren. Zie andere ondersteunde formaten hieronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}