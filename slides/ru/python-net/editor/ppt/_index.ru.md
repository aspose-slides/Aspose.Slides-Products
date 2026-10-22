---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Редактировать PPT в Python
url: /ru/python-net/editor/ppt/
keywords: Редактировать PPT, Редактировать PowerPoint, PPT, PowerPoint, API Python, библиотеку Python
description: Редактировать PPT в Python. Используйте API библиотеки Python для редактирования презентации PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Редактировать PPT в Python" h2="Высокоскоростная и кроссплатформенная библиотека Python для редактирования PPT с использованием кода Python." related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Редактировать PPT в Python" variant="code" %}}

Используя [**Aspose.Slides для Python через .NET**](https://products.aspose.com/slides/ru/python-net/), вы можете добавить новую строку текста в документ PPT всего за несколько секунд. строки кода.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код Python для редактирования PPT" >}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Редактировать PPT с помощью Aspose.Slides" %}}

[**Aspose.Slides для Python через .NET**](https://products.aspose.com/slides/ru/python-net/) — это мощная библиотека Python, используемая для управления и редактирования презентаций. Вы можете отредактировать презентацию PPT, добавив в нее новую строку текста.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как редактировать PPT в Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте библиотеку в качестве ссылки в свой проект.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите презентацию PPT, которую хотите отредактировать.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте новую строку текста.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните измененный файл PowerPoint.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Редактировать другие файлы" subTitle="Вы также можете редактировать файлы в других форматах" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
