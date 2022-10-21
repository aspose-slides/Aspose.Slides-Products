---
title: 使用 Python 合併 PDF、PPT、PPTX 和許多其他文件格式
url: /zh-hant/python-net/merge/
keywords: 合併、加入、PowerPoint、演示文稿、Python、Aspose
description: 合併 Python PPT、PPTX、ODP、PDF、PNG、JPG 等多個文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Python 中將 Powerpoint、PDF、PPT 或其他文檔合併在一起" h2="用於合併 PPT、PPTX、PDF、PNG、JPEG 等格式的高速 Python 庫。" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Python 合併 PPT、PPTX、PDF" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個強大的 Python 庫，用於創建和操作演示文件。此外，它提供了靈活的方式來組合多個 PPT/PPTX 演示文稿。當您將一個演示文稿合併到另一個演示文稿時，您實際上是將他們的幻燈片合併到一個演示文稿中以獲得一個文件。 Aspose.Slides 允許您以不同的方式合併兩個演示文稿。您可以將演示文稿與其所有形狀、樣式、文本、格式、評論、動畫等合併，而不必擔心質量或數據丟失。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 Python 中合併 PowerPoint 演示文稿" %}}
要合併 PowerPoint 演示文稿，您需要將幻燈片從一個演示文稿克隆到另一個演示文稿。

{{% blocks/products/pf/agp/code-block title="使用 Python 合併 PPTX 文件" offSpacer="true" %}}

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

{{% blocks/products/pf/feature-page-section  h2="使用 Python 將演示文稿與幻燈片母版合併" %}}
此 Python 代碼演示瞭如何將多個演示文稿合併為一個並應用幻燈片母版演示模板中的樣式。因此，結果演示文稿將保持相同的源格式，並將包含來自另一個演示文稿的母版幻燈片的格式。

{{% blocks/products/pf/agp/code-block title="在 Python 中將多個 PPT 合併為單個" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Python API 合併演示文稿" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 Python 中合併兩個 PPTX 文件並將結果保存為 PDF 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/)。
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 Python 項目。
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Python 中打開源 PPTX 文件。
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 **add_clone** 方法合併 PPTX 文件。
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存演示文稿並將結果保存為單個 PDF 文件。
```
pres1.save("document.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的合併格式" subTitle="您還可以組合其他文件格式。請參閱下面的其他支持的格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppt/" name="PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/pptx/" name="PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/pdf/" name="PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/odp/" name="ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/otp/" name="OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/pot/" name="POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/potm/" name="POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/potx/" name="POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/pps/" name="PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm/" name="PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsx/" name="PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/pptm/" name="PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/fodp/" name="FODP" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}