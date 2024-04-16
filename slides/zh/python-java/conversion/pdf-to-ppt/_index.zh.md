---
title: 在 Python 中将 PDF 转换为 PPT
url: /zh/python-java/conversion/pdf-to-ppt/
keywords: Python 演示文稿转换、将演示文稿转换为 Python、Python 演示文稿、Aspose.Slides Python、PDF 到 PPT 转换、Python 演示文稿库
description: 在 Python 中将 PDF 转换为 PPT。使用 Python 库 API 将 PDF 文件转换为 PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="使用 Python 轻松将 PDF 转换为 PPT：Aspose.Slides 来救援！" h2="使用 Python 为您的演示文稿注入新的活力。我们的指南将引导您将现有的 PowerPoint 幻灯片转换为引人入胜的 Python 演示文稿。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Python 中将 PDF 转换为 PPT" %}}

厌倦了与复杂的演示软件搏斗？ [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/zh/python-java/) 就是您的最佳选择！这个强大的库使您能够轻松创建、编辑演示文稿以及在各种格式之间转换演示文稿。需要从 PDF 切换到 PPT？ Aspose.Slides 使其变得轻而易举，只需要几行 Python 代码。

作为尖端的文档处理 API，**Aspose.Slides for Python via Java** 拥有闪电般的转换速度，确保将您的 PDF 演示文稿快速转换为 PPT 格式。摆脱传统工具的限制 - Aspose.Slides 使您能够灵活地将演示文稿从 PDF 转换为 PPT 以及各种其他格式，使您能够完美地适应任何情况的演示文稿。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 将 PDF 转换为 PPT" %}}
要将 PDF 转换为 PPT，您需要从 PDF 文件创建演示文稿并将其另存为 PPT。

{{% blocks/products/pf/agp/code-block title="将 PDF 转换为 PPT 的 Python 教程" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

pres.save("output.ppt", SaveFormat.Ppt);

jpype.shutdownJVM()

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python 教程。如何通过 Java API 使用 Aspose.Slides for Python 将 PDF 转换为 PPT。" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="要通过 Java 使用 Aspose.Slides for Python 将 PDF 转换为 PPT，您需要将包导入到 Python 脚本中并创建 Presenter 类的实例。 Presentation 类表示 PowerPoint 文档并提供访问和操作其元素的方法。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装[**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/zh/python-java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 Python 项目中。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Python 中打开源 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将结果保存为 PPT 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="将 PDF 转换为其他支持的格式" subTitle="您还可以转换 PDF 并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}