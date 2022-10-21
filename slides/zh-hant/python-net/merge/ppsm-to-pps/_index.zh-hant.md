---
title: 使用 Python 將 PPSM 文件合併到 PPS
url: /zh-hant/python-net/merge/ppsm-to-pps/
keywords: 將 PPSM 合併到 PPS，將 PPSM 連接到 PPS，將 PPSM 合併到 PPS，PowerPoint，演示文稿，PPS，Python，Aspose
description: 在 Python 中合併多個 PPSM 文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中將 PPSM 文件合併到 PPS" h2="高速和跨平台的 Python API，有助於開發應用程序，無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件即可創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Python 中將 PPSM 合併到 PPS" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個強大的 Python 庫，用於創建和操作演示文件。此外，它提供了靈活的方式來組合多個 PPSM 演示文稿。當您將一個演示文稿合併到另一個演示文稿時，您實際上是將他們的幻燈片合併到一個演示文稿中以獲得一個文件。 Aspose.Slides 允許您以不同的方式合併兩個演示文稿。您可以將演示文稿與其所有形狀、樣式、文本、格式、評論、動畫等合併，而不必擔心質量或數據丟失。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 將 PPSM 文件合併到 PPS" %}}
要合併 PowerPoint 演示文稿，您需要將幻燈片從一個演示文稿克隆到另一個演示文稿。

{{% blocks/products/pf/agp/code-block title="用於將多個 PPSM 合併為單個 PPS 文件的 Python 代碼" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.ppsm") as pres1:
    with slides.Presentation("presentation2.ppsm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pps", slides.export.SaveFormat.PPS)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Python API 將 PPSM 合併到 PPS" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 Python 中合併兩個 PPSM 文件並將結果保存為 PPS 的步驟。" >}}

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
在 Python 中打開源 PPSM 文件。
```
pres1 = slides.Presentation('pres1.ppsm')
pres2 = slides.Presentation('pres2.ppsm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) 方法合併 PPSM 文件。
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存演示文稿並將結果保存為單個 PPS 文件。
```
pres1.save("presentation.pps", slides.export.SaveFormat.PPS)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 PPSM 導出為其他支持的格式" subTitle="您還可以組合 PPSM 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-pptx/" name="PPSM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-ppt/" name="PPSM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-pdf/" name="PPSM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-html/" name="PPSM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-png/" name="PPSM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-bmp/" name="PPSM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-jpg/" name="PPSM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-fodp/" name="PPSM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-gif/" name="PPSM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-odp/" name="PPSM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-otp/" name="PPSM TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-pot/" name="PPSM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-potm/" name="PPSM TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-potx/" name="PPSM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-pptm/" name="PPSM TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-svg/" name="PPSM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-tiff/" name="PPSM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/ppsm-to-xps/" name="PPSM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}