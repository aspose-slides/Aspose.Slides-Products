---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Python 中将 HTML 转换为 PPT
url: /zh/python-net/conversion/html-to-ppt/
keywords: 将 HTML 转换为 PPT、将 HTML 转换为 PPT、PowerPoint、HTML、PPT、Python API、Python 库
description: 在 Python 中将 HTML 转换为 PPT。使用 Python 库 API 将 HTML 转换为 PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Python 中将 HTML 转换为 PPT" h2="强大的跨平台 Python API，用于使用 Python 代码将 HTML 转换为 PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中将 HTML 转换为 PPT" variant="code" %}}

使用 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/)，只需几行代码即可将 HTML 文档转换为 PowerPoint 演示文稿：

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML转PPT的Python代码" >}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rb") as htmlStream:
        pres.slides.add_from_html(htmlStream)

    pres.save("MyPresentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 将 HTML 转换为 PPT" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/) 是一个强大的 Python 库，用于创建、转换和操作 PowerPoint 演示文稿、PDF、 HTML 文档和其他文件。将 HTML 转换为 PPT 时，实际上是将 HTML 文档中的内容移动到 PowerPoint 演示文稿中的幻灯片。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Python 中将 HTML 转换为 PPT" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}通过 .NET 安装 **Aspose.Slides for Python**。请参阅 [**安装**](https://docs.aspose.com/slides/python-net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库添加为项目中的参考。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建一个 Presentation 类的实例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加载要转换为 PPT 的 HTML 文档。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将生成的文件另存为 PPT 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免费在线转换器"
  description="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的 PowerPoint 转换" subTitle="您还可以将其他格式的文件转换为 PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/jpg-to-ppt/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/jpg-to-pptx/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
