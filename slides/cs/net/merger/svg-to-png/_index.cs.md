---
title: Sloučit SVG do PNG v C#
url: /cs/net/merger/svg-to-png/
keywords: Sloučit SVG do PNG, SVG do PNG, Připojit SVG k PNG, Kombinovat SVG do PNG, C# API, .NET Library
description: Sloučit SVG do PNG v C#. Ke kombinaci souborů SVG a PNG použijte rozhraní API knihovny .NET
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Sloučit SVG do PNG v C#" h2="Výkonné rozhraní .NET API pro různé platformy pro slučování obrázků SVG do PNG pomocí kódu C# na platformách NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Sloučit SVG do PNG pomocí Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) je výkonná knihovna .NET používaná ke slučování a manipulaci s prezentacemi, obrázky a dalšími soubory. Když sloučíte SVG do PNG, efektivně kombinujete obrázky SVG a získáte obrázek PNG.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Sloučit SVG do PNG v C#" %}}
Pomocí [**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) můžete rychle sloučit soubory SVG do PNG pomocí několika řádků kódu

{{% blocks/products/pf/agp/code-block title="C# kód pro sloučení SVG do PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    ISvgImage svgImage = new SvgImage("doc.svg");
    IPPImage image = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    ISvgImage svgImage2 = new SvgImage("doc.svg");
    IPPImage image2 = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak sloučit SVG do PNG v C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Apose.Slides for .NET**. Viz [**Instalace**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte knihovnu jako referenci do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte soubory SVG, které chcete sloučit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledný obrázek PNG.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Sloučit další soubory" subTitle="Můžete také kombinovat soubory v jiných formátech a získat tak jeden soubor" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}