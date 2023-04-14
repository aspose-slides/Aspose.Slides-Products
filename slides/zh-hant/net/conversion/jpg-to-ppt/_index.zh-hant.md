---
title: 在 C# 中將 JPG 轉換為 PPT
url: /zh-hant/net/conversion/jpg-to-ppt/
keywords: 將 JPG 轉換為 PPT、將 JPG 轉換為 PPT、PowerPoint、JPG、PPT、C# API、.NET 庫
description: 在 C# 中將 JPG 轉換為 PPT。使用 .NET 庫 API 將 JPG 圖像轉換為 PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C# 中將 JPG 轉換為 PPT" h2="強大的跨平台 .NET API，用於在 NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上使用 C# 代碼將 JPG 轉換為 PPT" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 將 JPG 轉換為 PPT" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh-hant/net/) 是一個功能強大的 .NET 庫，用於創建、轉換和操作 PowerPoint 演示文稿、PDF、HTML 文檔、和其他文件。將 JPG 轉換為 PPT 時，實際上是在創建包含基於 JPG 圖像的幻燈片的 PowerPoint 演示文稿。

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="在 C# 中將 JPG 轉換為 PPT" %}}
使用 [**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh-hant/net/)，您只需幾行代碼就可以將 JPG 圖像轉換為 PowerPoint 演示文稿：

{{% blocks/products/pf/agp/code-block title="將JPG轉PPT的C#代碼" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在C#中將JPG轉換為PPT" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安裝 **Aspose.Slides for .NET**。請參閱 [**安裝**](https://docs.aspose.com/slides/net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加庫作為項目中的引用。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建一個 Presentation 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要轉換為 PPT 的 JPG 圖像。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將生成的文件另存為 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免費在線轉換器" sectionDescription="[如何在 Python 中將 PPT 轉換為 HTML](https://products.aspose.com/slides/zh-hant/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的 PowerPoint 轉換" subTitle="您還可以將其他格式的文件轉換為 PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}