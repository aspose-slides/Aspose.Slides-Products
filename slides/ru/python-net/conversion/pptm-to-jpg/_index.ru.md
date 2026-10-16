---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PPTM в JPG в Python
weight: 2480
url: /ru/python-net/conversion/pptm-to-jpg/ 
keywords: "Convert, PowerPoint, PPTM, JPG, Presentation, Python"
description: Пример кода для преобразования PPTM в JPG Python. Используйте PowerPoint Python API для пакетного преобразования файлов PPTM в файлы JPG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PPTM в JPG в Python" h2="Мощная библиотека PowerPoint Python для преобразования PPTM в JPG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PPTM в JPG в Python" %}}

Нужно программно преобразовать файлы PPTM в JPG? С помощью [*Aspose.Slides for Python через .NET*](https://products.aspose.com/slides/ru/python-net/) любой разработчик может преобразовать PPTM в формат JPG всего несколькими строками кода Python.

Как современный API обработки презентаций, Aspose.Slides для Python быстро создает JPG из PPTM. Проверьте качество преобразования PPTM в JPG прямо в вашем [браузере](https://products.aspose.app/slides/conversion/ppt-to-jpg). Библиотека Aspose PowerPoint PPTX позволяет конвертировать файлы PPTM во многие популярные форматы.

Вы можете установить библиотеку из [PyPI](https://pypi.org/project/Aspose.Slides/), используя следующую команду pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Консоль/терминал" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Сохранить PPTM как JPG в Python" %}}

Используйте бесплатное приложение, чтобы увидеть демонстрацию процесса преобразования PPTM в JPG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Этот пример кода показывает преобразование PPTM в JPG Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать PPTM в JPG в Python" intro="Это шаги для преобразования файла PPTM в JPG с использованием Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTM с экземпляром класса Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.JPG в качестве параметров.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Файл PPTM будет сохранен по указанному пути{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Перед запуском исходного кода примера преобразования Python убедитесь, что выполнены следующие предварительные условия." %}}

- ОС на базе Microsoft Windows или Linux (см. [подробнее](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 или новее
- Aspose.Slides for Python упоминается в вашем проекте.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатное приложение для преобразования PPTM в JPG"
  description="[Попробуйте наше бесплатное приложение, чтобы преобразовать PPT в JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPTM во многие другие форматы файлов. Смотрите другие поддерживаемые преобразования ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Растровое изображение" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="Расширенный формат метафайла" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="Плоская XML-презентация OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Графический формат обмена" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-html/" name="PPTM TO HTML" description="Язык гипертекстовой разметки" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Формат презентации OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Стандартный формат OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Портативный формат документа" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-png/" name="PPTM TO PNG" description="Портативная сетевая графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Формат презентации Open XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Масштабируемая векторная графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF-формат" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Формат изображения с тегами" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
