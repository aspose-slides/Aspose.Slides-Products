---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 对 PPT 演示文稿中的文本进行脱敏
url: /zh/python-net/redaction/ppt/
description: 使用 Python 查找并替换 PPT 演示文稿中的敏感文本。
keywords: PPT 脱敏，在 PPT 中查找和替换文本，更新 PPT 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 对 PPT 演示文稿中的文本进行脱敏" h2="借助 Aspose.Slides 构建在演示文稿中查找并替换敏感文本的 Python 应用程序。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 对 PPT 演示文稿中的文本脱敏" variant="code" %}}

借助 [Aspose.Slides for Python via .NET](/slides/zh/python-net/)，您可以替换整个 PPT 演示文稿中的敏感文本。将 `Presentation.replace_text` 与 `TextSearchOptions` 结合使用来控制搜索，然后保存修改后的演示文稿。

{{< blocks/products/pf/slides-design-update-10-2026/code title="对 PPT 演示文稿中的文本进行脱敏 – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 对 PPT 演示文稿中的文本进行脱敏" intro="按照以下步骤替换 PPT 演示文稿中的敏感文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 打开 PPT 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将 [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) 与 `TextSearchOptions` 结合使用，替换所需文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 保存修改后的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="基于 Aspose.Slides 构建" title="在线对 PPT 文件进行脱敏" description="免费的 Aspose.Slides Redaction 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Redaction" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找和替换文本。
- 在您的 PPT 文件中查找和替换文本，支持正则表达式。
- 下载脱敏后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持脱敏的格式" subTitle="使用 Python 对其他受支持的演示文稿格式中的文本进行脱敏。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
