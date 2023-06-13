---
title: .NET を使用して、PPTX プレゼンテーション ファイルにウォーターマークを追加します
url: /ja/net/watermark/pptx/
keywords: ウォーターマークの追加 PPTX、テキストのウォーターマークの追加 PPTX、画像のウォーターマークの追加 PPTX
description: PPTX プレゼンテーションにウォーターマークを追加するための C# ソース コード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# を使用して PPTX プレゼンテーションにウォーターマークを追加します" h2="独自の .NET アプリを構築し、サーバー側 API を使用してテキストまたは画像の透かしを PPT、PPTX、または ODP プレゼンテーションに挿入します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# 経由で PPTX プレゼンテーションにウォーターマークを追加します" %}}
Aspose.Slides for .NET を使用すると、PPTX プレゼンテーションにウォーターマークを追加できます。ウォーターマークはプレゼンテーションに不可欠な部分です。これらは、プレゼンテーションのコンテンツが許可なくコピーまたは使用されないように保護するために使用されます。ウォーターマークは、プレゼンテーションの上に配置される、表示または非表示の画像またはテキストです。プレゼンテーションの所有者を特定し、不正使用を防ぐために使用できます。透かしを使用すると、プレゼンテーションにプロフェッショナルな雰囲気を加え、より洗練された外観にすることもできます。 
{{% blocks/products/pf/agp/code-block title="C# を使用してテキスト透かしを PPTX に追加します" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/code-block title="C# を使用して画像ウォーターマークを PPTX プレゼンテーションに追加します" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="C# 経由で PPTX にウォーターマークを追加する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PPTX ファイルにテキストの透かしを追加する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスで PPTX を読み込みます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
マスタープレゼンテーションを選択してください
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape メソッドを使用して形状タイプを追加する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame メソッドを使用して透かしテキストを追加する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPTX 形式で保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている形式" subTitle="C# を使用すると、次の形式にウォーターマークを追加することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}