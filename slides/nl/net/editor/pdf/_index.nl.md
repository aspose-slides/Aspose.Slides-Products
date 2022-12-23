---
title: PDF bewerken in C#
url: /nl/net/editor/pdf/
keywords: PDF, PDF, C# API, .NET-bibliotheek bewerken
description: Pdf bewerken in C#. Gebruik de .NET-bibliotheek-API om PDF-documenten te bewerken
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PDF bewerken in C#" h2="Krachtige platformonafhankelijke .NET API voor het bewerken van PDF met C#-code op NET Framework-, .NET Core-, Windows Azure-, Mono- of Xamarin-platforms" >}}

{{% blocks/products/pf/feature-page-section h2="PDF bewerken met Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/nl/net/) is een krachtige .NET-bibliotheek die wordt gebruikt om presentaties, pdf-documenten en andere bestanden te manipuleren en te bewerken. U kunt een PDF-document bewerken door er een nieuwe regel tekst aan toe te voegen. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PDF bewerken in C#" %}}
Met [**Aspose.Slides for .NET**](https://products.aspose.com/slides/nl/net/) kunt u met slechts een paar regels code een nieuwe regel tekst toevoegen aan een PDF-document.

{{% blocks/products/pf/agp/code-block title="C#-code voor het bewerken van PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PDF bewerken in C#" >}}


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
Laad het PDF-document dat u wilt bewerken.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een nieuwe regel tekst toe.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het gewijzigde PDF-bestand op.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}