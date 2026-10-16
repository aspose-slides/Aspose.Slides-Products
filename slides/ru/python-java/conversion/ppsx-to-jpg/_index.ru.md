---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PPSX в JPG в Python
url: /ru/python-java/conversion/ppsx-to-jpg/
keywords: Преобразование презентаций Python, преобразование презентаций в Python, Python для презентаций, Aspose.Slides Python, преобразование PPSX в JPG, библиотека презентаций Python
description: Преобразуйте PPSX в JPG в Python. Используйте API библиотеки Python для преобразования файлов PPSX в JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Легко конвертируйте PPSX в JPG с помощью Python: Aspose.Slides спешит на помощь!" h2="Вдохните новую жизнь в свои презентации с помощью Python. Наше руководство поможет вам преобразовать существующие слайды PowerPoint в интересные презентации Python." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PPSX в JPG с помощью Python" variant="code" %}}

Чтобы преобразовать PPSX в JPG, вам нужно будет создать презентацию из файла PPSX и сохранить ее как JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Учебник по Python для преобразования PPSX в JPG" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppsx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PPSX в JPG в Python" %}}

Устали бороться со сложным программным обеспечением для презентаций? Не ищите ничего, кроме [**Aspose.Slides для Python через Java**](https://products.aspose.com/slides/ru/python-java/)! Эта мощная библиотека позволяет вам с легкостью создавать, редактировать и конвертировать презентации в различные форматы. Хотите переключиться с PPSX на JPG? Aspose.Slides упрощает задачу, требуя всего лишь нескольких строк кода Python.

Являясь передовым API обработки документов, **Aspose.Slides for Python через Java** может похвастаться молниеносной скоростью преобразования, гарантируя быстрое преобразование ваших презентаций PPSX в формат JPG. Откажитесь от ограничений традиционных инструментов — Aspose.Slides предоставляет вам возможность конвертировать презентации из PPSX не только в JPG, но и в широкий спектр других форматов, позволяя вам безупречно адаптировать свои презентации к любой ситуации.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Учебник по Python. Как преобразовать PPSX в JPG с помощью Aspose.Slides для Python через Java API." intro="Чтобы преобразовать PPSX в JPG с помощью Aspose.Slides for Python через Java, вам необходимо импортировать пакет в ваш скрипт Python и создать экземпляр класса Presentation. Класс Presentation представляет документ PowerPoint и предоставляет методы для доступа к его элементам и управления ими." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides for Python через Java**](https://products.aspose.com/slides/ru/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы PPSX в Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Преобразование PPSX в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PPSX и сохранять в другие форматы файлов. Все поддерживаемые форматы см. ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
