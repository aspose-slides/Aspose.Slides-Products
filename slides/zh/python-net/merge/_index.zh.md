---
title: 使用 Python 合并 PDF、PPT、PPTX 和许多其他文件格式
url: /zh/python-net/merge/
keywords: 合并、加入、PowerPoint、演示文稿、Python、Aspose
description: 合并 Python PPT、PPTX、ODP、PDF、PNG、JPG 等多个文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Python 中将 Powerpoint、PDF、PPT 或其他文档合并在一起" h2="用于合并 PPT、PPTX、PDF、PNG、JPEG 等格式的高速 Python 库。" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Python 合并 PPT、PPTX、PDF" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh/python-net/) 是一个强大的 Python 库，用于创建和操作演示文件。此外，它提供了灵活的方式来组合多个 PPT/PPTX 演示文稿。当您将一个演示文稿合并到另一个演示文稿时，您实际上是将他们的幻灯片合并到一个演示文稿中以获得一个文件。 Aspose.Slides 允许您以不同的方式合并两个演示文稿。您可以将演示文稿与其所有形状、样式、文本、格式、评论、动画等合并，而不必担心质量或数据丢失。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 Python 中合并 PowerPoint 演示文稿" %}}
要合并 PowerPoint 演示文稿，您需要将幻灯片从一个演示文稿克隆到另一个演示文稿。

{{% blocks/products/pf/agp/code-block title="使用 Python 合并 PPTX 文件" offSpacer="true" %}}

```python

import aspose.slides as slides

# open first presentation
with slides.Presentation("presentation1.pptx") as pres1:
    # open second presentation
    with slides.Presentation("presentation2.pptx") as pres2:
        # loop through slides
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
        # save merged presentation
        pres1.save("combined.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 将演示文稿与幻灯片母版合并" %}}
此 Python 代码演示了如何将多个演示文稿合并为一个并应用幻灯片母版演示模板中的样式。因此，结果演示文稿将保持相同的源格式，并将包含来自另一个演示文稿的母版幻灯片的格式。

{{% blocks/products/pf/agp/code-block title="在 Python 中将多个 PPT 合并为单个" offSpacer="true" %}}

```python

import aspose.slides as slides

files = ['pres1.pptx', 'pres2.pptx', 'pres3.pptx']

with slides.Presentation('master.pptx') as master:
    masterSlide = master.masters[0]

    for file in files:
        with slides.Presentation(file) as source:
            for slide in source.slides:
                clone = master.slides.add_clone(slide)

                for shape in masterSlide.shapes:
                    clone.shapes.add_clone(shape)
    
    master.save("combined.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Python API 合并演示文稿" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是在 Python 中合并两个 PPTX 文件并将结果保存为 PDF 的步骤。" >}}

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
在 Python 中打开源 PPTX 文件。
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 **add_clone** 方法合并 PPTX 文件。
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存演示文稿并将结果保存为单个 PDF 文件。
```
pres1.save("document.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的合并格式" subTitle="您还可以组合其他文件格式。请参阅下面的其他支持格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/ppt/" name="PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pptx/" name="PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pdf/" name="PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/odp/" name="ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/otp/" name="OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pot/" name="POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/potm/" name="POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/potx/" name="POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pps/" name="PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/ppsm/" name="PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/ppsx/" name="PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/pptm/" name="PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/merge/fodp/" name="FODP" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}