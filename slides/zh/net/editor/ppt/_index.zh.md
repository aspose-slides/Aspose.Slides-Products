---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 用C#编辑PPT
url: /zh/net/editor/ppt/
keywords: 编辑 PPT, 编辑 PowerPoint, PPT, PowerPoint, C# API, .NET Library
description: 用C#编辑PPT。使用 .NET 库 API 编辑 PowerPoint 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="用C#编辑PPT" h2="强大的跨平台 .NET API，用于在 NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上使用 C# 代码编辑 PPT" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="用C#编辑PPT" variant="code" %}}

使用 [**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh/net/)，您只需几行代码即可向 PPT 文档添加新的文本行。

{{< blocks/products/pf/slides-design-update-10-2026/code title="编辑PPT的C#代码" >}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 编辑 PPT" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh/net/) 是一个功能强大的 .NET 库，用于操作和编辑演示文稿。您可以通过向其中添加新的文本行来编辑 PPT 演示文稿。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在C#中编辑PPT" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 **Aspose.Slides for .NET**。请参阅 [**安装**](https://docs.aspose.com/slides/net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库添加为项目中的参考。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建一个 Presentation 类的实例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加载要编辑的 PPT 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加新的文本行。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存更改后的 PowerPoint 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
