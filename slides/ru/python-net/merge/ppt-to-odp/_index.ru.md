---
title: Объединить файлы PPT в ODP с помощью Python
url: /ru/python-net/merge/ppt-to-odp/
keywords: Объединить PPT в ODP, объединить PPT в ODP, объединить PPT в ODP, PowerPoint, презентацию, ODP, Python, Aspose
description: Объедините несколько файлов PPT в Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Объедините файлы PPT в ODP вместе в Python" h2="Высокоскоростной и кроссплатформенный Python API, который помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Объединить PPT в ODP в Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ru/python-net/) — мощная библиотека Python для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы объединения нескольких презентаций PPT. Когда вы объединяете одну презентацию с другой, вы эффективно объединяете их слайды в одну презентацию, чтобы получить один файл. Aspose.Slides позволяет объединять две презентации разными способами. Вы можете объединять презентации со всеми их формами, стилями, текстами, форматированием, комментариями, анимацией и т. д., не беспокоясь о потере качества или данных.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Объединить файлы PPT в ODP с помощью Python" %}}
Чтобы объединить презентации PowerPoint, вам нужно клонировать слайды из одной презентации в другую.

{{% blocks/products/pf/agp/code-block title="Код Python для объединения нескольких PPT в один файл ODP" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.ppt") as pres1:
    with slides.Presentation("presentation2.ppt") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как объединить PPT с ODP с помощью Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для объединения двух файлов PPT и сохранения результата как ODP в Python." >}}

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
Откройте исходные файлы PPT в Python.
```
pres1 = slides.Presentation('pres1.ppt')
pres2 = slides.Presentation('pres2.ppt')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Объедините PPT файлы, используя метод [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните презентацию и получите результат в виде одного файла ODP.
```
pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Экспорт PPT в другие поддерживаемые форматы" subTitle="Вы также можете комбинировать PPT и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-pptx/" name="PPT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-pdf/" name="PPT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-html/" name="PPT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-png/" name="PPT TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-bmp/" name="PPT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-jpg/" name="PPT TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-fodp/" name="PPT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-gif/" name="PPT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-otp/" name="PPT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-pot/" name="PPT TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-potm/" name="PPT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-potx/" name="PPT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-pps/" name="PPT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-ppsm/" name="PPT TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-ppsx/" name="PPT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-pptm/" name="PPT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-svg/" name="PPT TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-tiff/" name="PPT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/ppt-to-xps/" name="PPT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}