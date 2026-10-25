---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 从 PPTX 文件中提取文本
url: /zh/python-net/parser/pptx/
description: 使用 Python 从 PPTX 演示文稿中提取文本和文本格式详细信息。
keywords: 使用 Python 解析 PPTX, PPTX 解析器 Python, 在 Python 中从 PPTX 提取数据, 使用 Python 从 PPTX 提取文本
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 从 PPTX 演示文稿中提取文本" h2="构建使用 Aspose.Slides 从 PowerPoint 演示文稿中提取文本和格式详细信息的 Python 应用程序。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 从 PPTX 演示文稿中提取文本的示例" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/zh/python-net/) 在 `SlideUtil` 上提供静态方法 [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/)。它返回整个演示文稿的 `TextFrame` 对象，并且可以包含母版幻灯片中的文本。以下示例从 PPTX 演示文稿中提取文本和相关的字体详细信息。

{{< blocks/products/pf/slides-design-update-10-2026/code title="从 PPTX 演示文稿中提取文本 - Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 从 PPTX 中提取文本" intro="按照以下步骤从 PPTX 文件中提取文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 打开 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `SlideUtil.get_all_text_frames` 并指定是否包含母版幻灯片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历返回的 `TextFrame` 对象。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历每个文本框的 `paragraphs` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历每个段落的 `portions` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}读取当前部分的 `text` 和格式属性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="基于 Aspose.Slides 构建" title="在线提取文本和图像" description="免费的 Aspose.Slides Parser 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Parser" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何读取您的文件。
- 上传 PPTX 文件，获取其中的文本和图像。
- 将所有内容下载为一个 ZIP 压缩包。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持解析的格式" subTitle="使用 Python，还可以从其他受支持的演示文稿格式中提取文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
