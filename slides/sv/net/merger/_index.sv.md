---
title: Slå samman PDF, PPT, PPTX och många andra filformat med C#
url: /sv/net/merger/
keywords: Sammanfoga, gå med, PowerPoint, Presentation, C#, .NET, Aspose
description: Slå samman flera filer i C# PPT, PPTX, ODP, PDF, PNG, JPG och många fler.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Slå ihop Powerpoint, PDF, PPT eller andra dokument i C#" h2="Höghastighets C#-bibliotek för att slå samman PPT, PPTX, PDF, PNG, JPEG och andra format." >}}

{{% blocks/products/pf/feature-page-section h2="Slå samman PPT, PPTX, PDF med C#" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) är ett kraftfullt C#-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att kombinera flera PPT/PPTX-presentationer. När du slår samman en presentation med en annan, kombinerar du effektivt deras bilder i en enda presentation för att få en fil. Aspose.Slides låter dig slå samman två presentationer på olika sätt. Du får sammanfoga presentationer med alla deras former, stilar, texter, formatering, kommentarer, animationer, etc. utan att behöva oroa dig för förlust av kvalitet eller data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Slå samman PowerPoint-presentationer i C#" %}}
För att slå samman PowerPoint-presentationer måste du klona bilderna från en presentation till den andra.

{{% blocks/products/pf/agp/code-block title="Slå samman PPTX-filer med C#" offSpacer="true" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Slå samman presentationer med Slide Master med C#" %}}
Den här C#-koden visar hur man slår samman flera presentationer till en och applicerar stilar från presentationsmall för bildspel. Så resultatpresentationen kommer att behålla samma källformatering och kommer att innehålla formatering från huvudbilden i en annan presentation.

{{% blocks/products/pf/agp/code-block title="Slå ihop flera PPT till singel i C#" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Hur man slår samman presentationer med Aspose.Slides för .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Detta är stegen för att slå samman två PPTX-filer och spara resultatet som PDF i .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt C#-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna käll-PPTX-filerna i C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinera PPTX-filer med **AddClone**-metoden.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara presentationen och få resultatet som en enda PDF-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra format som stöds att slå samman" subTitle="Du kan också kombinera andra filformat. Se andra format som stöds nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}