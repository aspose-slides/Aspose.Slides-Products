---
title: Watermerk toevoegen aan PPT presentatiebestanden met .NET
url: /nl/net/watermark/ppt/
keywords: Watermerk toevoegen PPT, Tekstwatermerk toevoegen PPT, Afbeeldingswatermerk toevoegen PPT
description: C# broncode voor het toevoegen van watermerk aan PPT presentatie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Watermerk toevoegen aan presentatie PPT met behulp van C#" h2="Bouw uw eigen .NET-apps om tekst- of afbeeldingswatermerken in PPT-, PPTX- of ODP-presentaties in te voegen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Watermerk toevoegen aan presentatie PPT via C#" %}}
Met Aspose.Slides for .NET kunt u een watermerk toevoegen aan de PPT-presentatie. Watermerken zijn een essentieel onderdeel van elke presentatie. Ze worden gebruikt om te voorkomen dat de inhoud van de presentatie zonder toestemming wordt gekopieerd of gebruikt. Een watermerk is een zichtbare of onzichtbare afbeelding of tekst die bovenop de presentatie wordt geplaatst. Het kan worden gebruikt om de eigenaar van de presentatie te identificeren en ongeoorloofd gebruik te voorkomen. Watermerken kunnen ook worden gebruikt om een ​​professionele toets aan de presentatie te geven en deze er verzorgder uit te laten zien. 
{{% blocks/products/pf/agp/code-block title="Voeg tekstwatermerk toe aan PPT met C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Afbeeldingswatermerk toevoegen aan presentatie PPT met behulp van C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Watermerk toevoegen aan PPT via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om een ​​tekstwatermerk toe te voegen aan PPT-bestanden." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPT met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Selecteer de masterpresentatie
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vormtype toevoegen met de methode AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg watermerktekst toe met de methode AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPT formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde formaten" subTitle="Met C# kunt u ook een watermerk toevoegen aan de volgende indelingen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}