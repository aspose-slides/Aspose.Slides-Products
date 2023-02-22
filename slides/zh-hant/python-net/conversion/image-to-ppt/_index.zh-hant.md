---
title: 在 Python 中將圖像轉換為 PPT
url: /zh-hant/python-net/conversion/image-to-ppt/
keywords: 圖像轉 PPT、圖像轉 PPT、Python API、Python 庫、圖像、PPT
description: 在 Python 中將圖像轉換為 PPT。使用 Python 庫 API 將圖像文件轉換為 PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中將圖像轉換為 PPT" h2="高速和跨平台的 Python 庫，有助於開發能夠創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的應用程序，而無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Python 中將圖像轉換為 PPT" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個強大的 Python 庫，用於創建和操作演示文稿文件。此外，它還提供了將圖像轉換為 PPT 的靈活方法。使用 **Aspose.Slides for Python via .NET**，任何開發人員或應用程序只需幾行 Python 代碼即可將圖像轉換為 PPT 文件。

作為現代文檔處理API，Aspose.Slides for Python 可快速將圖像文件導出為PPT 文件格式。 Aspose PowerPoint 庫允許您將圖像轉換為 PDF 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 將圖像轉換為 PPT" %}}
要將圖像轉換為 PPT，您需要從圖像文件創建演示文稿並將其另存為 PPT。

{{% blocks/products/pf/agp/code-block title="圖片轉PPT的Python代碼" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.ppt", slides.export.SaveFormat.PPT)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Python API 將圖像轉換為 PPT" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 Python 中將圖像轉換為 PPT 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 Python 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Python 中打開源圖像文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PPT 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將圖像轉換為其他支持的格式" subTitle="您還可以轉換圖像並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}