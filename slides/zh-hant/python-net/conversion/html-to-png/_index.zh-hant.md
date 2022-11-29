---
title: 在 Python 中將 HTML 轉換為 PNG
url: /zh-hant/python-net/conversion/html-to-png/
keywords: HTML 到 PNG，將 HTML 轉換為 PNG，Python API，Python 庫，HTML，PNG
description: 在 Python 中將 HTML 轉換為 PNG。使用 Python 庫 API 將 HTML 文件轉換為 PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中將 HTML 轉換為 PNG" h2="高速和跨平台的 Python 庫，有助於開發能夠創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的應用程序，而無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Python 中將 HTML 轉換為 PNG" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個強大的 Python 庫，用於創建和操作演示文稿文件。此外，它提供了將 HTML 轉換為 PNG 的靈活方法。使用 **Aspose.Slides for Python via .NET**，任何開發人員或應用程序只需幾行 Python 代碼即可將 HTML 轉換為 PNG 文件。

作為現代文檔處理 API，Aspose.Slides for Python 可快速將 HTML 文件導出為 PNG 文件格式。 Aspose PowerPoint 庫允許您將 HTML 轉換為 PNG 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 將 HTML 轉換為 PNG" %}}
要將 HTML 轉換為 PNG，您需要從 HTML 文件創建演示文稿並將其另存為 PNG。

{{% blocks/products/pf/agp/code-block title="將 HTML 轉換為 PNG 的 Python 代碼" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open(dataDir + "file.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Python API 將 HTML 轉換為 PNG" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 Python 中將 HTML 轉換為 PNG 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 Python 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Python 中打開源 HTML 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PNG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 HTML 轉換為其他支持的格式" subTitle="您還可以轉換 HTML 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}