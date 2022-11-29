---
title: 在 Python 中将 JPG 转换为 Image
url: /zh/python-net/conversion/jpg-to-image/
keywords: JPG 到 Image，将 JPG 转换为 Image，Python API，Python 库，JPG，Image
description: 在 Python 中将 JPG 转换为 Image。使用 Python 库 API 将 JPG 文件转换为 Images
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中将 JPG 转换为 Image" h2="高速和跨平台的 Python 库，有助于开发能够创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的应用程序，而无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Python 中将 JPG 转换为 Image" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/) 是一个强大的 Python 库，用于创建和操作演示文稿文件。此外，它提供了将 JPG 转换为 Image 的灵活方法。使用 **Aspose.Slides for Python via .NET**，任何开发人员或应用程序只需几行 Python 代码即可将 JPG 转换为 Image 文件。

作为现代文档处理 API，Aspose.Slides for Python 可快速将 JPG 文件导出为 Image 文件格式。 Aspose PowerPoint 库允许您将 JPG 转换为 Image 和许多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 将 JPG 转换为 Image" %}}
要将 JPG 转换为 Image，您需要从 JPG 文件创建演示文稿并将其另存为 Image。

{{% blocks/products/pf/agp/code-block title="将 JPG 转换为 Image 的 Python 代码" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Python API 将 JPG 转换为 Image" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是在 Python 中将 JPG 转换为 Image 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 Python 项目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Python 中打开源 JPG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将结果保存为 Image 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="将 JPG 转换为其他支持的格式" subTitle="您还可以转换 JPG 并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}