---
title: Vízjel hozzáadása a PPT prezentációs fájlokhoz a .NET használatával
url: /hu/net/watermark/ppt/
keywords: Vízjel hozzáadása PPT, Szöveg vízjel hozzáadása PPT, Kép vízjel hozzáadása PPT
description: C# forráskód vízjel hozzáadásához a PPT prezentációhoz.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vízjel hozzáadása a PPT prezentációhoz a C# használatával" h2="Készítse el saját .NET alkalmazásait, amellyel szöveget vagy képet illeszthet be PPT-, PPTX- vagy ODP-prezentációba szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Vízjel hozzáadása a PPT prezentációhoz a C# segítségével" %}}
A Aspose.Slides for .NET használatával vízjelet adhat a PPT prezentációhoz. A vízjelek minden prezentáció elengedhetetlen részét képezik. Arra szolgálnak, hogy megvédjék a prezentáció tartalmát az engedély nélküli másolástól vagy felhasználástól. A vízjel egy látható vagy láthatatlan kép vagy szöveg, amely a prezentáció tetejére kerül. Segítségével azonosítható a prezentáció tulajdonosa, és megakadályozható a jogosulatlan használat. A vízjelek arra is használhatók, hogy professzionális hatást keltsenek a prezentációban, és még csiszoltabbnak tűnjenek. 
{{% blocks/products/pf/agp/code-block title="Szöveges vízjel hozzáadása a PPT fájlhoz a C# használatával" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/code-block title="Kép vízjel hozzáadása a PPT prezentációhoz a C# használatával" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Vízjel hozzáadása a PPT fájlhoz a C# segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a szöveges vízjel hozzáadásához a PPT fájlokhoz." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPT betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Válassza ki a fő bemutatót
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá alaktípust az AddAutoShape módszerrel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá vízjelszöveget az AddTextFrame módszerrel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPT formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott formátumok" subTitle="A C# használatával a következő formátumokhoz is hozzáadhat vízjelet:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}