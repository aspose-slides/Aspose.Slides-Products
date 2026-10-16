---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование JPG в Image в Python
url: /ru/python-net/conversion/jpg-to-image/
keywords: JPG в Image, преобразовать JPG в Image, Python API, библиотеку Python, JPG, Image
description: Преобразуйте JPG в Image в Python. Используйте API библиотеки Python для преобразования файлов JPG в файлы Image.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование JPG в Image в Python" h2="Высокоскоростная и кроссплатформенная библиотека Python, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование JPG в Image с помощью Python" variant="code" %}}

Чтобы преобразовать JPG в Image, вам нужно будет создать презентацию из файла JPG и сохранить его как Image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код Python для преобразования JPG в Image" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование JPG в Image в Python" %}}

[**Aspose.Slides для Python через .NET**](https://products.aspose.com/slides/ru/python-net/) — мощная библиотека Python для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования JPG в Image. Используя **Aspose.Slides для Python через .NET**, любой разработчик или приложение может преобразовать файлы JPG в Image всего несколькими строками кода Python.

Как современный API обработки документов, Aspose.Slides for Python быстро экспортирует файлы JPG в форматы файлов Image. Библиотека Aspose PowerPoint позволяет конвертировать JPG в Image и многие другие форматы файлов.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать JPG в Image с помощью Aspose.Slides for Python API" intro="Это шаги для преобразования JPG в Image в Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ru/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы JPG в Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл Image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатный онлайн-конвертер"
  description="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Конвертировать JPG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать JPG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
