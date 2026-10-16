---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование POTX в SVG в Python
weight: 1510
url: /ru/python-net/conversion/potx-to-svg/ 
keywords: "Convert, PowerPoint, POTX, SVG, Presentation, Python"
description: Пример кода для преобразования POTX в SVG Python. Используйте PowerPoint Python API для пакетного преобразования файлов POTX в файлы SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование POTX в SVG в Python" h2="Мощная библиотека PowerPoint Python для преобразования POTX в SVG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование POTX в SVG в Python" %}}

Нужно программно преобразовать файлы POTX в SVG? С помощью [*Aspose.Slides for Python через .NET*](https://products.aspose.com/slides/ru/python-net/) любой разработчик может преобразовать POTX в формат SVG всего несколькими строками кода Python.

Как современный API обработки презентаций, Aspose.Slides for Python быстро создает SVG из POTX. Проверьте качество преобразования POTX в SVG прямо в вашем [браузере](https://products.aspose.app/slides/conversion). Библиотека Aspose PowerPoint PPTX позволяет конвертировать файлы POTX во многие популярные форматы.

Вы можете установить библиотеку из [PyPI](https://pypi.org/project/Aspose.Slides/), используя следующую команду pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Консоль/терминал" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Сохранить POTX как SVG в Python" %}}

Используйте бесплатное приложение, чтобы увидеть демонстрацию процесса преобразования POTX в SVG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Этот пример кода показывает преобразование POTX в SVG Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potx") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать POTX в SVG в Python" intro="Это шаги для преобразования файла POTX в SVG с использованием Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл POTX с экземпляром класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.SVG в качестве параметров.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POTX-файл будет сохранен по указанному пути.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Перед запуском исходного кода примера преобразования Python убедитесь, что выполнены следующие предварительные условия." %}}

- ОС на базе Microsoft Windows или Linux (см. [подробнее](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 или новее
- Aspose.Slides for Python упоминается в вашем проекте.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатное приложение для преобразования POTX в SVG"
  description="[Попробуйте наше бесплатное приложение Video](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать POTX во многие другие форматы файлов. Смотрите другие поддерживаемые преобразования ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-bmp/" name="POTX TO BMP" description="Растровое изображение" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-emf/" name="POTX TO EMF" description="Расширенный формат метафайла" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-fodp/" name="POTX TO FODP" description="Плоская XML-презентация OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-gif/" name="POTX TO GIF" description="Графический формат обмена" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-html/" name="POTX TO HTML" description="Язык гипертекстовой разметки" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-jpg/" name="POTX TO JPG" description="Изображение в формате JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-odp/" name="POTX TO ODP" description="Формат презентации OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-otp/" name="POTX TO OTP" description="Стандартный формат OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-pdf/" name="POTX TO PDF" description="Портативный формат документа" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-png/" name="POTX TO PNG" description="Портативная сетевая графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-pot/" name="POTX TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-potm/" name="POTX TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-pps/" name="POTX TO PPS" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Файл презентации с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Формат презентации Open XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-swf/" name="POTX TO SWF" description="SWF-формат" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Формат изображения с тегами" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/potx-to-xps/" name="POTX TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
