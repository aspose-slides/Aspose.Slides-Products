---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PDF в PNG в Python
url: /ru/python-java/conversion/pdf-to-png/
keywords: Преобразование презентаций Python, преобразование презентаций в Python, Python для презентаций, Aspose.Slides Python, преобразование PDF в PNG, библиотека презентаций Python
description: Преобразуйте PDF в PNG в Python. Используйте API библиотеки Python для преобразования файлов PDF в PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Легко конвертируйте PDF в PNG с помощью Python: Aspose.Slides спешит на помощь!" h2="Вдохните новую жизнь в свои презентации с помощью Python. Наше руководство поможет вам преобразовать существующие слайды PowerPoint в интересные презентации Python." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PDF в PNG с помощью Python" variant="code" %}}

Чтобы преобразовать PDF в PNG, вам нужно будет создать презентацию из файла PDF и сохранить ее как PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Учебник по Python для преобразования PDF в PNG" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PDF в PNG в Python" %}}

Устали бороться со сложным программным обеспечением для презентаций? Не ищите ничего, кроме [**Aspose.Slides для Python через Java**](https://products.aspose.com/slides/ru/python-java/)! Эта мощная библиотека позволяет вам с легкостью создавать, редактировать и конвертировать презентации в различные форматы. Хотите переключиться с PDF на PNG? Aspose.Slides упрощает задачу, требуя всего лишь нескольких строк кода Python.

Являясь передовым API обработки документов, **Aspose.Slides for Python через Java** может похвастаться молниеносной скоростью преобразования, гарантируя быстрое преобразование ваших презентаций PDF в формат PNG. Откажитесь от ограничений традиционных инструментов — Aspose.Slides предоставляет вам возможность конвертировать презентации из PDF не только в PNG, но и в широкий спектр других форматов, позволяя вам безупречно адаптировать свои презентации к любой ситуации.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Учебник по Python. Как преобразовать PDF в PNG с помощью Aspose.Slides для Python через Java API." intro="Чтобы преобразовать PDF в PNG с помощью Aspose.Slides for Python через Java, вам необходимо импортировать пакет в ваш скрипт Python и создать экземпляр класса Presentation. Класс Presentation представляет документ PowerPoint и предоставляет методы для доступа к его элементам и управления ими." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides for Python через Java**](https://products.aspose.com/slides/ru/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы PDF в Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Преобразование PDF в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PDF и сохранять в другие форматы файлов. Все поддерживаемые форматы см. ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
