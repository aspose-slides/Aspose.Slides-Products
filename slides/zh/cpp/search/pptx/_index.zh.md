---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 在 PPTX 演示文稿中搜索文本
url: /zh/cpp/search/pptx/
description: 在 C++ 中搜索 PPTX 演示文稿中的文本。使用 Aspose.Slides for C++ 查找演示文稿文件中的文本。
keywords: 在 PPTX 中搜索单词，在 PPTX 中查找文本，搜索 PPTX 演示文稿文本
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 在 PPTX 中搜索文本" h2="使用 Aspose.Slides for C++ 查找演示文稿文件中的文本，无需 Microsoft PowerPoint。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 C++ 在 PPTX 演示文稿中搜索文本" variant="code" %}}

Aspose.Slides for C++ 可用于在 PPTX 演示文稿中搜索文本。使用 `SlideUtil::GetAllTextBoxes` 收集幻灯片的文本框架，然后检查其文本是否包含所需短语。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 在单个 PPTX 演示文稿中搜索文本" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 C++ 在 PPTX 中搜索文本" intro="按照以下步骤在 PPTX 演示文稿中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation::get_Slides` 获取所需幻灯片，并使用 [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) 获取其文本框架。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}检查每个框架的文本是否包含所需短语。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="基于 Aspose.Slides 构建" title="在线搜索 PPTX 文件中的文本" description="免费的 Aspose.Slides Search 应用基于 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Search" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找文本。
- 在您的 PPTX 文件中搜索纯文本或正则表达式。
- 将匹配结果下载为文本文件。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持搜索的格式" subTitle="使用 C++，您还可以在以下格式中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
