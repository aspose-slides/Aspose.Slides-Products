---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Python 中将 PPTX 转换为 BMP
weight: 2650
url: /zh/python-net/conversion/pptx-to-bmp/ 
keywords: "Convert, PowerPoint, PPTX, BMP, Presentation, Python"
description: PPTX 到 BMP Python 转换的示例代码。使用 PowerPoint Python API 将 PPTX 文件批量转换为 BMP 文件。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Python 中将 PPTX 转换为 BMP" h2="强大的 PowerPoint Python 库，用于将 PPTX 转换为 BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中将 PPTX 转换为 BMP" %}}

需要以编程方式将 PPTX 文件转换为 BMP？使用 [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/zh/python-net/) 任何开发人员只需几行 Python 代码即可将 PPTX 转换为 BMP 格式。

作为现代演示处理 API，Aspose.Slides for Python 可以快速从 PPTX 创建 BMP。在您的 [浏览器](https://products.aspose.app/slides/conversion) 中测试 PPTX 到 BMP 转换的质量。 Aspose PowerPoint PPTX 库允许您将 PPTX 文件转换为许多流行的格式。

您可以使用以下 pip 命令从 [PyPI](https://pypi.org/project/Aspose.Slides/) 安装库：

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="控制台/终端" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中将 PPTX 保存为 BMP" %}}

使用免费应用程序查看 PPTX 到 BMP 转换过程的演示。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代码显示 PPTX 到 BMP Python 转换" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Python 中将 PPTX 转换为 BMP" intro="这些是使用 Python 将 PPTX 文件转换为 BMP 的步骤。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 类的实例加载 PPTX 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定输出文件路径和 SaveFormat.BMP 作为参数时调用 `save` 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX文件将保存在指定路径{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="在运行 Python 转换示例源代码之前，请确保您具有以下先决条件。" %}}

- 基于 Microsoft Windows 或 Linux 的操作系统（参见 [更多](https://docs.aspose.com/slides/python-net/system-requirements/)）。
- Python 3.5 或更高版本
- 项目中引用的 Python Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pptx-to-bmp"
  title="免費應用程序將PPTX轉換為BMP"
  description="[嘗試我們的免費應用程序將PPT轉換為BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 PPTX 转换为许多其他文件格式。请参阅下面的其他支持的转换" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="增强的元文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="图形交换格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-html/" name="PPTX TO HTML" description="超文本标记语言" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="JPEG图像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument 标准格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="便携式文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-png/" name="PPTX TO PNG" description="便携式网络图形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="微软 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="幻灯片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="启用宏的幻灯片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="幻灯片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="微软PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="启用宏的演示文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="可缩放矢量图形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="标记图像格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/python-net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
