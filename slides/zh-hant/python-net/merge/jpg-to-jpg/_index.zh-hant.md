---
title: 在 Python 中合併 JPG 圖像
url: /zh-hant/python-net/merge/jpg-to-jpg/
keywords: 合併 JPG、JPEG 到 JPG、加入 JPG、合併 JPG、Python API、Python 庫
description: 在 Python 中將 JPG 合併為 JPG。使用 Python 庫 API 合併 JPG 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Python 中合併 JPG" h2="用於使用 Python 代碼合併 JPG 圖像的高速跨平台 Python 庫" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 將 JPG 合併為 JPG" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/) 是一個功能強大的 Python 庫，用於合併和操作演示文稿、圖像和其他文件。當您將 JPG 合併為 JPG 時，實際上是將兩張圖像組合成一張圖片。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 Python 中將 JPG 合併為 JPG" %}}
使用 [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/zh-hant/python-net/)，只需幾行代碼即可快速合併 JPG 文件

{{% blocks/products/pf/agp/code-block title="將 JPG 合併為 JPG 的 Python 代碼" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image1 = pres.images.add_image(drawing.Bitmap("image1.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 100, 100, image1)

    image2 = pres.images.add_image(drawing.Bitmap("image2.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 200, 100, 100, image2)

    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.jpeg)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Python 中合併 JPG" >}}


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
加載要合併為相框的 JPG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 JPG 圖像。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="在線合併 PDF 文件" sectionDescription="[如何在 Python 中合併 PDF](https://products.aspose.com/slides/zh-hant/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="合併其他文件" subTitle="您還可以合併其他格式的文件以獲得單個文件" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}