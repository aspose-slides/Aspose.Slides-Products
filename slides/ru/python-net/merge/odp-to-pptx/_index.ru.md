---
title: Объединить файлы ODP в PPTX с помощью Python
url: /ru/python-net/merge/odp-to-pptx/
keywords: Объединить ODP в PPTX, объединить ODP в PPTX, объединить ODP в PPTX, PowerPoint, презентацию, PPTX, Python, Aspose
description: Объедините несколько файлов ODP в Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Объедините файлы ODP в PPTX вместе в Python" h2="Высокоскоростной и кроссплатформенный Python API, который помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Объединить ODP в PPTX в Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ru/python-net/) — мощная библиотека Python для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы объединения нескольких презентаций ODP. Когда вы объединяете одну презентацию с другой, вы эффективно объединяете их слайды в одну презентацию, чтобы получить один файл. Aspose.Slides позволяет объединять две презентации разными способами. Вы можете объединять презентации со всеми их формами, стилями, текстами, форматированием, комментариями, анимацией и т. д., не беспокоясь о потере качества или данных.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Объединить файлы ODP в PPTX с помощью Python" %}}
Чтобы объединить презентации PowerPoint, вам нужно клонировать слайды из одной презентации в другую.

{{% blocks/products/pf/agp/code-block title="Код Python для объединения нескольких ODP в один файл PPTX" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.odp") as pres1:
    with slides.Presentation("presentation2.odp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как объединить ODP с PPTX с помощью Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для объединения двух файлов ODP и сохранения результата как PPTX в Python." >}}

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
Откройте исходные файлы ODP в Python.
```
pres1 = slides.Presentation('pres1.odp')
pres2 = slides.Presentation('pres2.odp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Объедините ODP файлы, используя метод [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните презентацию и получите результат в виде одного файла PPTX.
```
pres1.save("presentation.pptx", slides.export.SaveFormat.PPTX)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Экспорт ODP в другие поддерживаемые форматы" subTitle="Вы также можете комбинировать ODP и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-ppt/" name="ODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-pdf/" name="ODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-html/" name="ODP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-png/" name="ODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-bmp/" name="ODP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-jpg/" name="ODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-fodp/" name="ODP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-gif/" name="ODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-otp/" name="ODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-pot/" name="ODP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-potm/" name="ODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-potx/" name="ODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-pps/" name="ODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-ppsm/" name="ODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-ppsx/" name="ODP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-pptm/" name="ODP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-svg/" name="ODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-tiff/" name="ODP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/odp-to-xps/" name="ODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}