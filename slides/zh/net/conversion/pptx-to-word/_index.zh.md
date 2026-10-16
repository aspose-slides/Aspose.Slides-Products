---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 C# 中将 PPTX 转换为 Word
url: /zh/net/conversion/pptx-to-word/
keywords: 将 PPTX 转换为 Word、将 PPTX 转换为 Word、将 PPTX 转换为 DOC、将 PowerPoint 转换为 Word、C# API、.NET 库
description: 在 C# 中将 PPTX 转换为 Word。使用 .NET 库 API 将 PowerPoint 转换为 Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C# 中将 PPTX 转换为 Word" h2="强大的跨平台 .NET API，用于在 NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上使用 C# 代码将 PowerPoint 转换为 Word" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 C# 中将 PowerPoint 转换为 Word" variant="code" %}}

只需几行代码，即可快速将PPTX转Word

{{< blocks/products/pf/slides-design-update-10-2026/code title="用于将 PowerPoint 转换为 Word 的 C# 代码" >}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 和 Aspose.Words 将 PowerPoint 转换为 Word" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh/net/) 和 [**Aspose.Words for .NET**](https://products.aspose. com/words/net/) 是功能强大的 .NET 库，用于操作和转换 PowerPoint 演示文稿、Word 文档和其他文件。将 PowerPoint 转换为 Word 时，实际上是将演示文稿幻灯片的内容移动到 Word 文档中的页面。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何将 PPTX 转换为 Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 **Aspose.Slides for .NET** 和 **Aspose.Words for .NET**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加这两个库作为项目中的引用。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建 Presentation 类和 Doc 类的实例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加载要转换为 Word 的 PPTX 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}根据幻灯片的内容生成图像和文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存生成的 Word 文档。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免费在线转换器"
  description="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 PowerPoint 转换为其他格式的文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
