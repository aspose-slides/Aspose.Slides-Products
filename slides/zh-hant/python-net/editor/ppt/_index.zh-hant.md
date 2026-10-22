---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Python 中編輯 PPT
url: /zh-hant/python-net/editor/ppt/
keywords: 編輯 PPT, 編輯 PowerPoint, PPT, PowerPoint, Python API, Python Library
description: 用 Python 編輯 PPT。使用 Python 庫 API 編輯 PowerPoint 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Python 中編輯 PPT" h2="用於使用 Python 代碼編輯 PPT 的高速跨平台 Python 庫" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中編輯 PPT" variant="code" %}}

使用 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/)，您只需幾行就可以向 PPT 文檔添加新的文本行代碼行。

{{< blocks/products/pf/slides-design-update-10-2026/code title="編輯PPT的Python代碼" >}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 編輯 PPT" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個功能強大的 Python 庫，用於操作和編輯演示文稿。您可以通過向其中添加新的文本行來編輯 PPT 演示文稿。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Python 中編輯 PPT" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}通過 .NET 安裝 **Aspose.Slides for Python**。請參閱 [**安裝**](https://docs.aspose.com/slides/python-net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加庫作為項目中的引用。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}創建一個 Presentation 類的實例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加載要編輯的 PPT 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加新的文本行。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存更改後的 PowerPoint 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="編輯其他文件" subTitle="您還可以編輯其他格式的文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
