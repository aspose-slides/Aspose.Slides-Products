---
title: Объединить файлы PPTX в JPG с помощью Python
url: /ru/python-net/merge/pptx-to-jpg/
keywords: Объединить PPTX в JPG, объединить PPTX в JPG, объединить PPTX в JPG, PowerPoint, презентацию, JPG, Python, Aspose
description: Объедините несколько файлов PPTX в Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Объедините файлы PPTX в JPG вместе в Python" h2="Высокоскоростной и кроссплатформенный Python API, который помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Объединить PPTX в JPG в Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ru/python-net/) — мощная библиотека Python для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы объединения нескольких презентаций PPTX. Когда вы объединяете одну презентацию с другой, вы эффективно объединяете их слайды в одну презентацию, чтобы получить один файл. Aspose.Slides позволяет объединять две презентации разными способами. Вы можете объединять презентации со всеми их формами, стилями, текстами, форматированием, комментариями, анимацией и т. д., не беспокоясь о потере качества или данных.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Объединить файлы PPTX в JPG с помощью Python" %}}
Чтобы объединить презентации PowerPoint, вам нужно клонировать слайды из одной презентации в другую.

{{% blocks/products/pf/agp/code-block title="Код Python для объединения нескольких PPTX в один файл JPG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.pptx") as pres1:
    with slides.Presentation("presentation2.pptx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как объединить PPTX с JPG с помощью Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для объединения двух файлов PPTX и сохранения результата как JPG в Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ru/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Python.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы PPTX в Python.
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Объедините PPTX файлы, используя метод [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните презентацию и получите результат в виде одного файла JPG.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Экспорт PPTX в другие поддерживаемые форматы" subTitle="Вы также можете комбинировать PPTX и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-ppt/" name="PPTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-pdf/" name="PPTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-html/" name="PPTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-png/" name="PPTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-bmp/" name="PPTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-fodp/" name="PPTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-gif/" name="PPTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-odp/" name="PPTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-otp/" name="PPTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-pot/" name="PPTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-potm/" name="PPTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-potx/" name="PPTX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-pps/" name="PPTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-ppsm/" name="PPTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-ppsx/" name="PPTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-pptm/" name="PPTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-svg/" name="PPTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-tiff/" name="PPTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/pptx-to-xps/" name="PPTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}