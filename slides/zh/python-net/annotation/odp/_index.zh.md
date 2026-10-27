---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: 使用 Python 从 ODP 中删除评论
url: /zh/python-net/annotation/odp/ 
description: 借助 Aspose.Slides for Python via .NET，使用 Python 从 ODP 演示文稿中删除评论和评论作者。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 从 ODP 中删除评论和评论作者" h2="使用 Aspose.Slides for Python via .NET 删除演示文稿评论及其关联作者。" related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Python 从 ODP 中删除评论" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/zh/python-net/) 可访问 ODP 演示文稿中存储的评论和评论作者。使用 `Presentation` 加载文件，清空每位作者的 `comments` 集合，清空 `comment_authors`，然后以 ODP 格式保存结果。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Python 从 ODP 中删除评论" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 Python 从 ODP 中删除评论" intro="按照以下步骤从 ODP 演示文稿中删除所有评论和评论作者。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 打开 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历 `comment_authors` 并清空每位作者的 `comments` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}清空 `comment_authors` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.ODP` 调用 `save`，写入更新后的 ODP 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="基于 Aspose.Slides 构建" title="在线删除 ODP 评论" description="免费的 Aspose.Slides Annotation 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 ODP 文件。" button="打开 Aspose.Slides Annotation" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何删除评论。
- 删除 ODP 文件中的所有评论。
- 下载清理后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="批注支持的其他格式" subTitle="使用 Python，您还可以从其他格式中删除批注。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
