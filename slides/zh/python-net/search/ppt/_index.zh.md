---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 在 PPT 演示文稿中搜索文本
url: /zh/python-net/search/ppt/
description: 使用 Python 和 Aspose.Slides 在 PPT 演示文稿中搜索文本。
keywords: 在 PPT 中搜索文本，在 PPT 中查找单词，使用 Python 搜索 PPT 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 在 PPT 演示文稿中搜索文本" h2="借助 Aspose.Slides 构建在 PowerPoint 演示文稿中查找文本的 Python 应用程序。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 在单个 PPT 演示文稿中搜索文本" variant="code" %}}

借助 [Aspose.Slides for Python via .NET](/slides/zh/python-net/)，您可以使用 [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) 在每张幻灯片上查找包含指定字符串的文本框架。

{{< blocks/products/pf/slides-design-update-10-2026/code title="在 PPT 演示文稿中搜索文本 – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 在 PPT 中搜索文本" intro="按照以下步骤在 PPT 演示文稿中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 打开 PPT 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历幻灯片，并对每张幻灯片调用 [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}读取每个匹配文本框架的 `text` 属性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="基于 Aspose.Slides 构建" title="在线搜索 PPT 文件中的文本" description="免费的 Aspose.Slides Search 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Search" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找文本。
- 在您的 PPT 文件中搜索纯文本或正则表达式。
- 将匹配结果下载为文本文件。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持搜索的格式" subTitle="使用 Python 在其他受支持的演示文稿格式中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
