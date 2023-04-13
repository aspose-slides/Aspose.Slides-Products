---
title: 在 C# 中将 JPG 转换为 PPT
url: /zh/net/conversion/jpg-to-ppt/
keywords: 将 JPG 转换为 PPT、将 JPG 转换为 PPT、PowerPoint、JPG、PPT、C# API、.NET 库
description: 在 C# 中将 JPG 转换为 PPT。使用 .NET 库 API 将 JPG 图像转换为 PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C# 中将 JPG 转换为 PPT" h2="强大的跨平台 .NET API，用于在 NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上使用 C# 代码将 JPG 转换为 PPT" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 将 JPG 转换为 PPT" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh/net/) 是一个功能强大的 .NET 库，用于创建、转换和操作 PowerPoint 演示文稿、PDF、HTML 文档、和其他文件。将 JPG 转换为 PPT 时，实际上是在创建包含基于 JPG 图像的幻灯片的 PowerPoint 演示文稿。

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="在 C# 中将 JPG 转换为 PPT" %}}
使用 [**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh/net/)，您只需几行代码就可以将 JPG 图片转换为 PowerPoint 演示文稿：

{{% blocks/products/pf/agp/code-block title="将JPG转PPT的C#代码" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="如何在C#中将JPG转换为PPT" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安装 **Aspose.Slides for .NET**。请参阅 [**安装**](https://docs.aspose.com/slides/net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库添加为项目中的参考。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建一个 Presentation 类的实例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加载要转换为 PPT 的 JPG 图像。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将生成的文件另存为 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免费在线转换器" sectionDescription="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的 PowerPoint 转换" subTitle="您还可以将其他格式的文件转换为 PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}