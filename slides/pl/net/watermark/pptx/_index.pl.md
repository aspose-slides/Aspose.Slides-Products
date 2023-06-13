---
title: Dodaj znak wodny do PPTX plików prezentacji za pomocą .NET
url: /pl/net/watermark/pptx/
keywords: Dodaj znak wodny PPTX, Dodaj tekstowy znak wodny PPTX, Dodaj graficzny znak wodny PPTX
description: Kod źródłowy C# do dodawania znaku wodnego do prezentacji PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Dodaj znak wodny do PPTX prezentacji za pomocą C#" h2="Twórz własne aplikacje .NET, aby wstawiać tekstowy lub graficzny znak wodny do prezentacji PPT, PPTX lub ODP za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Dodaj znak wodny do PPTX prezentacji za pośrednictwem C#" %}}
Za pomocą Aspose.Slides for .NET możesz dodać znak wodny do prezentacji PPTX. Znaki wodne są istotną częścią każdej prezentacji. Służą one ochronie treści prezentacji przed kopiowaniem lub wykorzystywaniem bez zezwolenia. Znak wodny to widoczny lub niewidoczny obraz lub tekst umieszczony w górnej części prezentacji. Może służyć do identyfikacji właściciela prezentacji i zapobiegania nieautoryzowanemu użyciu. Znaki wodne mogą również służyć do nadania prezentacji profesjonalnego charakteru i nadania jej bardziej dopracowanego wyglądu. 
{{% blocks/products/pf/agp/code-block title="Dodaj tekstowy znak wodny do PPTX za pomocą C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dodaj znak wodny obrazu do PPTX prezentacji za pomocą C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak dodać znak wodny do PPTX przez C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby dodać tekstowy znak wodny do plików PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPTX z instancją Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wybierz główną prezentację
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj typ kształtu za pomocą metody AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj tekst znaku wodnego za pomocą metody AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty" subTitle="Korzystając z C#, możesz również dodać znak wodny do następujących formatów:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}