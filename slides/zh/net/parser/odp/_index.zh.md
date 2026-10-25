---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: 使用 .NET 从 ODP 文件中提取文本
url: /zh/net/parser/odp/ 
description: 使用 .NET 从 ODP 文件中提取文本的 C# 源代码。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 解析 ODP 文件" h2="使用服务器端 .NET API 从 ODP 文件中提取文本并检查文本格式。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 解析 ODP 文件的方法" %}}

使用 [Aspose.Slides for .NET](/slides/zh/net/) 从 ODP 演示文稿中提取文本。从 [NuGet](https://www.nuget.org/packages/aspose.slides.net) 安装该包，或在程序包管理器控制台中运行以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="解析 ODP 文件 - C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 C# 中解析 ODP 文件" intro="使用 [Aspose.Slides for .NET](/slides/zh/net/) API 进行基本的文档解析只需几行代码。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 加载 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SlideUtil.GetAllTextFrames` 获取文本框。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历文本框、段落和文本部分。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}根据需要读取 `Text`、`FontHeight` 和 `LatinFont.FontName` 属性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="需要受支持的 .NET 运行时以及对 Aspose.Slides for .NET 包的引用。可以使用 Visual Studio 或其他兼容的 C# 开发环境。" %}}

- 兼容 .NET Framework、.NET、Mono 或 Xamarin 的环境
- Visual Studio 等 C# 开发环境
- 从 NuGet 安装的 Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="基于 Aspose.Slides 构建" title="在线提取文本和图像" description="免费的 Aspose.Slides Parser 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 ODP 文件。" button="打开 Aspose.Slides Parser" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何读取您的文件。
- 上传 ODP 文件，获取其中的文本和图像。
- 将所有内容下载为一个 ZIP 压缩包。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP files use the OpenDocument Presentation format. A presentation contains slides with text, images, formatting, animations, and other media. Applications that support the OpenDocument format, such as OpenOffice and StarOffice, can open ODP files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持解析的格式" subTitle="使用 C#，还可以解析以下格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/parser/ppt/" name="PPT" description="PowerPoint 97-2003 演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/parser/pptx/" name="PPTX" description="PowerPoint Open XML 演示文稿" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
