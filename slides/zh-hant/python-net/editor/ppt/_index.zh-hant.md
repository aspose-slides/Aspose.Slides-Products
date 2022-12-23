---
title: 在 Python 中編輯 PPT
url: /zh-hant/python-net/editor/ppt/
keywords: 編輯 PPT, 編輯 PowerPoint, PPT, PowerPoint, Python API, Python Library
description: 用 Python 編輯 PPT。使用 Python 庫 API 編輯 PowerPoint 演示文稿
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中編輯 PPT" h2="用於使用 Python 代碼編輯 PPT 的高速跨平台 Python 庫" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 編輯 PPT" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個功能強大的 Python 庫，用於操作和編輯演示文稿。您可以通過向其中添加新的文本行來編輯 PPT 演示文稿。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 Python 中編輯 PPT" %}}
使用 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/)，您只需幾行就可以向 PPT 文檔添加新的文本行代碼行。

{{% blocks/products/pf/agp/code-block title="編輯PPT的Python代碼" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Python 中編輯 PPT" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
通過 .NET 安裝 **Aspose.Slides for Python**。請參閱 [**安裝**](https://docs.aspose.com/slides/python-net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加庫作為項目中的引用。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建一個 Presentation 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要編輯的 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改後的 PowerPoint 文件。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="編輯其他文件" subTitle="您還可以編輯其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}