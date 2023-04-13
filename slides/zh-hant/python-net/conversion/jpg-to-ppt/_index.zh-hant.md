---
title: 在 Python 中將 JPG 轉換為 PPT
url: /zh-hant/python-net/conversion/jpg-to-ppt/
keywords: 將 JPG 轉換為 PPT、將 JPG 轉換為 PPT、PowerPoint、JPG、PPT、Python API、Python 庫
description: 在 Python 中將 JPG 轉換為 PPT。使用 Python 庫 API 將 JPG 圖片轉換為 PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中將 JPG 轉換為 PPT" h2="強大的跨平台 Python API，用於使用 Python 代碼將 JPG 轉換為 PPT" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 將 JPG 轉換為 PPT" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個功能強大的 Python 庫，用於創建、轉換和操作 PowerPoint 演示文稿、PDF、 HTML 文檔和其他文件。將 JPG 轉換為 PPT 時，實際上是在創建包含基於 JPG 圖像的幻燈片的 PowerPoint 演示文稿。

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="在 Python 中將 JPG 轉換為 PPT" %}}
使用 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/)，只需幾行代碼即可將 JPG 圖像轉換為 PowerPoint 演示文稿：

{{% blocks/products/pf/agp/code-block title="JPG轉PPT的Python代碼" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Python 中將 JPG 轉換為 PPT" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
通過 .NET 安裝 **Aspose.Slides for Python**。請參閱 [**安裝**](https://docs.aspose.com/slides/python-net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加庫作為項目中的引用。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建一個 Presentation 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要轉換為 PPT 的 JPG 圖像。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將生成的文件另存為 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免費在線轉換器" sectionDescription="[如何在 Python 中將 PPT 轉換為 HTML](https://products.aspose.com/slides/zh-hant/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的 PowerPoint 轉換" subTitle="您還可以將其他格式的文件轉換為 PowerPoint" >}}

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