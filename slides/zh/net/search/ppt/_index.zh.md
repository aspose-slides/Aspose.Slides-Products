---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 在 PPT 演示文稿文件中搜索文本
url: /zh/net/search/ppt/
description: 用于在 PPT 演示文稿中搜索文本的 C# 源代码。
keywords: 在 PPT 中搜索文本，在 PPT 中查找文本，搜索 PPT 演示文稿文本
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 在 PPT 文件中搜索文本" h2="构建通过服务器端 API 在演示文稿中查找文本的 .NET 应用。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 在 PPT 演示文稿中搜索文本" variant="code" %}}

借助 [Aspose.Slides for .NET](/slides/zh/net/)，您可以在 PPT 演示文稿中搜索文本。使用 `SlideUtil.GetAllTextBoxes` 获取幻灯片的文本框架，然后检查其 `Text` 值中是否包含所需短语。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 在 PPT 演示文稿中搜索文本" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 在 PPT 演示文稿中搜索文本" intro="按照以下步骤在 PPT 演示文稿中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 加载 PPT 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}从 `Presentation.Slides` 获取所需幻灯片并将其赋给变量。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) 获取其文本框架。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}检查每个框架的 `Text` 值是否包含所需短语。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="基于 Aspose.Slides 构建" title="在线搜索 PPT 文件中的文本" description="免费的 Aspose.Slides Search 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Search" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找文本。
- 在您的 PPT 文件中搜索纯文本或正则表达式。
- 将匹配结果下载为文本文件。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持搜索的格式" subTitle="使用 C#，您还可以在以下格式中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
