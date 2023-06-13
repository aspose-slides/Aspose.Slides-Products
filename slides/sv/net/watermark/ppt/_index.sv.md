---
title: Lägg till vattenstämpel i PPT presentationsfiler med .NET
url: /sv/net/watermark/ppt/
keywords: Lägg till vattenstämpel PPT, Lägg till textvattenstämpel PPT, Lägg till bildvattenstämpel PPT
description: Källkod för C# för att lägga till vattenstämpel i presentationen PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lägg till vattenstämpel i presentationen PPT med C#" h2="Bygg dina egna .NET-appar för att infoga text- eller bildvattenstämplar i PPT-, PPTX- eller ODP-presentationer med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till vattenstämpel i presentationen PPT via C#" %}}
Med Aspose.Slides for .NET kan du lägga till vattenstämpel i presentationen av PPT. Vattenstämplar är en viktig del av alla presentationer. De används för att skydda innehållet i presentationen från att kopieras eller användas utan tillstånd. En vattenstämpel är en synlig eller osynlig bild eller text som placeras ovanpå presentationen. Den kan användas för att identifiera ägaren till presentationen och för att förhindra obehörig användning. Vattenstämplar kan också användas för att sätta en professionell touch till presentationen och få den att se mer polerad ut. 
{{% blocks/products/pf/agp/code-block title="Lägg till textvattenstämpel i PPT med C#" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/code-block title="Lägg till bildvattenstämpel i PPT presentation med C#" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Så här lägger du till vattenstämpel i PPT via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att lägga till textvattenstämpel i PPT-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT med en instans av Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Välj huvudpresentationen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till formtyp med metoden AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till vattenstämpeltext med AddTextFrame-metoden
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra format som stöds" subTitle="Med C# kan du också lägga till vattenstämpel i följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}