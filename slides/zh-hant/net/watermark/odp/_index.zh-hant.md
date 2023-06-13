---
title: 使用 .NET 將水印添加到 ODP 演示文件
url: /zh-hant/net/watermark/odp/
keywords: 添加水印 ODP，添加文字水印 ODP，添加圖片水印 ODP
description: C# 源代碼，用於將水印添加到 ODP 演示文稿。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 C# 將水印添加到 ODP 演示文稿" h2="構建您自己的 .NET 應用程序，以使用服務器端 API 將文本或圖像水印插入到 PPT、PPTX 或 ODP 演示文稿中。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C# 為 ODP 演示文稿添加水印" %}}
使用 Aspose.Slides for .NET，您可以為 ODP 演示文稿添加水印。水印是任何演示文稿的重要組成部分。它們用於保護演示文稿的內容不被複製或未經許可使用。水印是放置在演示文稿頂部的可見或不可見的圖像或文本。它可用於識別演示文稿的所有者並防止未經授權的使用。水印也可用於為演示文稿增添專業氣息並使其看起來更加精美。 
{{% blocks/products/pf/agp/code-block title="使用 C# 將文本水印添加到 ODP" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="使用 C# 將圖像水印添加到 ODP 演示文稿" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 C# 為 ODP 添加水印" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是將文本水印添加到 ODP 文件的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 實例加載 ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
選擇主演示文稿
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 AddAutoShape 方法添加形狀類型
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 AddTextFrame 方法添加水印文本
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 ODP 格式保存結果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的格式" subTitle="使用C#，您還可以為以下格式添加水印：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}