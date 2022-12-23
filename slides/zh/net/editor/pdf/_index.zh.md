---
title: 在 C# 中编辑 PDF
url: /zh/net/editor/pdf/
keywords: 编辑 PDF、PDF、C# API、.NET 库
description: 在 C# 中编辑 PDF。使用 .NET 库 API 编辑 PDF 文档
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C# 中编辑 PDF" h2="强大的跨平台 .NET API，用于在 NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上使用 C# 代码编辑 PDF" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 编辑 PDF" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh/net/) 是一个功能强大的 .NET 库，用于操作和编辑演示文稿、PDF 文档和其他文件。您可以通过向其中添加新的文本行来编辑 PDF 文档。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 C# 中编辑 PDF" %}}
使用 [**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh/net/)，您只需几行代码即可向 PDF 文档添加新的文本行。

{{% blocks/products/pf/agp/code-block title="用于编辑 PDF 的 C# 代码" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 C# 中编辑 PDF" >}}


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
加载要编辑的 PDF 文档。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改后的 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}