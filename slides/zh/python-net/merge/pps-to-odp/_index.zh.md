---
title: 使用 Python 将 PPS 文件合并到 ODP
url: /zh/python-net/merge/pps-to-odp/
keywords: 将 PPS 合并到 ODP，将 PPS 连接到 ODP，将 PPS 合并到 ODP，PowerPoint，演示文稿，ODP，Python，Aspose
description: 在 Python 中合并多个 PPS 文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中将 PPS 文件合并到 ODP" h2="高速和跨平台的 Python API，有助于开发应用程序，无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件即可创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Python 中将 PPS 合并到 ODP" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/) 是一个强大的 Python 库，用于创建和操作演示文件。此外，它提供了灵活的方式来组合多个 PPS 演示文稿。当您将一个演示文稿合并到另一个演示文稿时，您实际上是将他们的幻灯片合并到一个演示文稿中以获得一个文件。 Aspose.Slides 允许您以不同的方式合并两个演示文稿。您可以将演示文稿与其所有形状、样式、文本、格式、评论、动画等合并，而不必担心质量或数据丢失。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 将 PPS 文件合并到 ODP" %}}
要合并 PowerPoint 演示文稿，您需要将幻灯片从一个演示文稿克隆到另一个演示文稿。

{{% blocks/products/pf/agp/code-block title="用于将多个 PPS 合并为单个 ODP 文件的 Python 代码" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pps") as pres1:
    with slides.Presentation("presentation2.pps") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Python API 将 PPS 合并到 ODP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是在 Python 中合并两个 PPS 文件并将结果保存为 ODP 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/)。
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 Python 项目。
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Python 中打开源 PPS 文件。
```
pres1 = slides.Presentation('pres1.pps')
pres2 = slides.Presentation('pres2.pps')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) 方法合并 PPS 文件。
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存演示文稿并将结果保存为单个 ODP 文件。
```
pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="在线合并 PDF 文件" sectionDescription="[如何在 Python 中合并 PDF](https://products.aspose.com/slides/zh/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="将 PPS 导出为其他支持的格式" subTitle="您还可以组合 PPS 并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-pptx/" name="PPS TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-ppt/" name="PPS TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-pdf/" name="PPS TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-html/" name="PPS TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-png/" name="PPS TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-bmp/" name="PPS TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-jpg/" name="PPS TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-fodp/" name="PPS TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-gif/" name="PPS TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-otp/" name="PPS TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-pot/" name="PPS TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-potm/" name="PPS TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-potx/" name="PPS TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-ppsm/" name="PPS TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-ppsx/" name="PPS TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-pptm/" name="PPS TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-svg/" name="PPS TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-tiff/" name="PPS TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps-to-xps/" name="PPS TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}