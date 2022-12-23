---
title: Bewerk PPT in C#
url: /nl/net/editor/ppt/
keywords: PPT bewerken, PowerPoint, PPT, PowerPoint, C# API, .NET-bibliotheek bewerken
description: Bewerk PPT in C#. Gebruik de .NET-bibliotheek-API om de PowerPoint-presentatie te bewerken
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bewerk PPT in C#" h2="Krachtige platformonafhankelijke .NET API voor het bewerken van PPT met behulp van C#-code op NET Framework-, .NET Core-, Windows Azure-, Mono- of Xamarin-platforms" >}}

{{% blocks/products/pf/feature-page-section h2="Bewerk PPT met Aspose.Slides" %}}

[**Aspose.Slides voor .NET**](https://products.aspose.com/slides/nl/net/) is een krachtige .NET-bibliotheek die wordt gebruikt om presentaties te manipuleren en te bewerken. U kunt een PPT-presentatie bewerken door er een nieuwe regel tekst aan toe te voegen. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Bewerk PPT in C#" %}}
Met [**Aspose.Slides for .NET**](https://products.aspose.com/slides/nl/net/) kunt u met slechts een paar regels code een nieuwe regel tekst toevoegen aan een PPT-document.

{{% blocks/products/pf/agp/code-block title="C#-code voor het bewerken van PPT" offSpacer="true" %}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hoe PPT in C# te bewerken" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installeer **Aspose.Slides voor .NET**. Zie [**Installatie**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg de bibliotheek toe als referentie in uw project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van de klasse Presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad de PPT-presentatie die u wilt bewerken.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een nieuwe regel tekst toe.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het gewijzigde PowerPoint-bestand op.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}