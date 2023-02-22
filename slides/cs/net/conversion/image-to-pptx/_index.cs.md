---
title: Převést obrázek na PPTX v C#
url: /cs/net/conversion/image-to-pptx/
keywords: Převést obrázek do PPTX, obrázek do PPTX, PowerPoint, obrázek, PPTX, C# API, .NET Library
description: Převést obrázek na PPTX v C#. K převodu obrázku do PowerPointu použijte rozhraní API knihovny .NET
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převést obrázek na PPTX v C#" h2="Výkonné rozhraní .NET API pro různé platformy pro převod obrazu na PPTX pomocí kódu C# na platformách NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte obrázek na PPTX pomocí Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) je výkonná knihovna .NET používaná k vytváření, převodu a manipulaci s prezentacemi v PowerPointu, PDF, HTML dokumenty, a další soubory. Když převedete obrázek na PPTX, v podstatě vytváříte prezentaci PowerPoint, která obsahuje snímky založené na těchto obrázcích.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Převést obrázek na PPTX v C#" %}}
Pomocí [**Aspose.Slides for .NET**](https://products.aspose.com/slides/cs/net/) můžete převést obrázek na prezentaci v PowerPointu pomocí několika řádků kódu:

{{% blocks/products/pf/agp/code-block title="C# kód pro převod obrázku do PPTX" offSpacer="true" %}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak převést obrázek na PPTX v C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides for .NET**. Viz [**Instalace**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte knihovnu jako referenci do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte obrázek, který chcete převést na PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledný soubor jako prezentaci PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Další podporované převody PowerPoint" subTitle="Můžete také převést soubory v jiných formátech do PowerPointu" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}