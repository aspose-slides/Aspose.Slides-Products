---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 对 PPTX 演示文稿文件进行脱敏
url: /zh/net/redaction/pptx/
description: 用于在 PPTX 演示文稿中查找和替换文本的 C# 源代码。
keywords: PPTX 脱敏，在 PPTX 中查找和替换文本，更新 PPTX 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 对 PPTX 文件进行脱敏" h2="构建通过服务器端 API 在演示文稿中查找和替换文本的 .NET 应用。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 对 PPTX 演示文稿进行脱敏" variant="code" %}}

借助 [Aspose.Slides for .NET](/slides/zh/net/)，您可以在 PPTX 演示文稿中查找和替换文本。将 `Presentation.ReplaceText` 与 `TextSearchOptions` 结合使用来控制搜索，然后保存修改后的演示文稿。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 对 PPTX 演示文稿进行脱敏" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 对 PPTX 演示文稿进行脱敏" intro="按照以下步骤替换 PPTX 演示文稿中的文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将 [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) 与 `TextSearchOptions` 结合使用，替换所需文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pptx` 保存修改后的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="基于 Aspose.Slides 构建" title="在线对 PPTX 文件进行脱敏" description="免费的 Aspose.Slides Redaction 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Redaction" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找和替换文本。
- 在您的 PPTX 文件中查找和替换文本，支持正则表达式。
- 下载脱敏后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持脱敏的格式" subTitle="使用 C#，您还可以对以下格式进行脱敏。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
