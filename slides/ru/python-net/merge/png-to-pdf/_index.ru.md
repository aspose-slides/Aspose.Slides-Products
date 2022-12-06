---
title: Объединить PNG в PDF в Python
url: /ru/python-net/merge/png-to-pdf/
keywords: PNG в PDF, Объединить PNG в PDF, Объединить PNG в PDF, PDF, PNG, Python API, Python Library
description: Слияние PNG в PDF в Python. Используйте API библиотеки Python для объединения PNG и PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Объединить PNG в PDF в Python" h2="Высокоскоростная и кроссплатформенная библиотека Python для объединения файлов PNG в PDF с использованием кода Python." >}}

{{% blocks/products/pf/feature-page-section h2="Объединение PNG в PDF с помощью Aspose.Slides" %}}

[**Aspose.Slides для Python через .NET**](https://products.aspose.com/slides/ru/python-net/) — это мощная библиотека Python, используемая для создания, преобразования, объединения и управления презентациями, изображениями , и другие файлы. Когда вы объединяете PNG в PDF, вы фактически объединяете изображения PNG для получения одного файла PDF.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Объединить PNG в PDF в Python" %}}
Используя [**Aspose.Slides для Python через .NET**](https://products.aspose.com/slides/ru/python-net/), вы можете быстро объединить PNG в PDF, написав всего несколько строк кода.

{{% blocks/products/pf/agp/code-block title="Код Python для объединения PNG в PDF" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image1 = pres.images.add_image(drawing.Bitmap("image1.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 100, 100, image1)

    image2 = pres.images.add_image(drawing.Bitmap("image2.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 200, 100, 100, image2)

    pres.save("pres.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как объединить PNG в PDF в Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте библиотеку в качестве ссылки в свой проект.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите изображения PNG, которые вы хотите объединить в качестве рамок для картин.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните полученный PDF-файл.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Объединить другие файлы" subTitle="Вы также можете комбинировать файлы в других форматах, чтобы получить один файл." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}