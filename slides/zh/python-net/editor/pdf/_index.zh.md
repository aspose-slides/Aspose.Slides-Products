---
title: 在 Python 中编辑 PDF
url: /zh/python-net/editor/pdf/
keywords: 编辑 PDF、PDF、Python API、Python 库
description: 在 Python 中编辑 PDF。使用 Python 库 API 编辑 PDF 文档
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中编辑 PDF" h2="用于使用 Python 代码编辑 PDF 的高速跨平台 Python 库" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 编辑 PDF" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/) 是一个功能强大的 Python 库，用于操作和编辑演示文稿、PDF 文档和其他文件.您可以通过向其中添加新的文本行来编辑 PDF 文档。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 Python 中编辑 PDF" %}}
使用 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/)，您只需几行即可将新的文本行添加到 PDF 文档代码行。

{{% blocks/products/pf/agp/code-block title="用于编辑PDF的Python代码" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Python 中编辑 PDF" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
通过 .NET 安装 **Aspose.Slides for Python**。请参阅 [**安装**](https://docs.aspose.com/slides/python-net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库添加为项目中的参考。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建一个 Presentation 类的实例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加载要编辑的 PDF 文档。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改后的 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}