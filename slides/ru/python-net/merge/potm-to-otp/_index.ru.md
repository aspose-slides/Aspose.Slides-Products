---
title: Объединить файлы POTM в OTP с помощью Python
url: /ru/python-net/merge/potm-to-otp/
keywords: Объединить POTM в OTP, объединить POTM в OTP, объединить POTM в OTP, PowerPoint, презентацию, OTP, Python, Aspose
description: Объедините несколько файлов POTM в Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Объедините файлы POTM в OTP вместе в Python" h2="Высокоскоростной и кроссплатформенный Python API, который помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Объединить POTM в OTP в Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ru/python-net/) — мощная библиотека Python для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы объединения нескольких презентаций POTM. Когда вы объединяете одну презентацию с другой, вы эффективно объединяете их слайды в одну презентацию, чтобы получить один файл. Aspose.Slides позволяет объединять две презентации разными способами. Вы можете объединять презентации со всеми их формами, стилями, текстами, форматированием, комментариями, анимацией и т. д., не беспокоясь о потере качества или данных.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Объединить файлы POTM в OTP с помощью Python" %}}
Чтобы объединить презентации PowerPoint, вам нужно клонировать слайды из одной презентации в другую.

{{% blocks/products/pf/agp/code-block title="Код Python для объединения нескольких POTM в один файл OTP" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.potm") as pres1:
    with slides.Presentation("presentation2.potm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.otp", slides.export.SaveFormat.OTP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как объединить POTM с OTP с помощью Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для объединения двух файлов POTM и сохранения результата как OTP в Python." >}}

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
Откройте исходные файлы POTM в Python.
```
pres1 = slides.Presentation('pres1.potm')
pres2 = slides.Presentation('pres2.potm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Объедините POTM файлы, используя метод [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните презентацию и получите результат в виде одного файла OTP.
```
pres1.save("presentation.otp", slides.export.SaveFormat.OTP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Экспорт POTM в другие поддерживаемые форматы" subTitle="Вы также можете комбинировать POTM и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-pptx/" name="POTM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-ppt/" name="POTM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-pdf/" name="POTM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-html/" name="POTM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-png/" name="POTM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-bmp/" name="POTM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-jpg/" name="POTM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-fodp/" name="POTM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-gif/" name="POTM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-odp/" name="POTM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-pot/" name="POTM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-potx/" name="POTM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-pps/" name="POTM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-ppsm/" name="POTM TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-ppsx/" name="POTM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-pptm/" name="POTM TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-svg/" name="POTM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-tiff/" name="POTM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/merge/potm-to-xps/" name="POTM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}