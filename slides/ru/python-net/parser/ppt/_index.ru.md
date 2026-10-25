---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Извлечение текста из файлов PPT на Python
url: /ru/python-net/parser/ppt/
description: Извлекайте текст и сведения о форматировании текста из презентаций PPT на Python.
keywords: разбор PPT на Python, парсер PPT Python, извлечение данных из PPT на Python, извлечение текста из PPT на Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Извлечение текста из презентаций PPT на Python" h2="Создавайте приложения на Python, которые с помощью Aspose.Slides извлекают текст и сведения о форматировании из презентаций PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Извлечение текста из презентации PPT на Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/ru/python-net/) предоставляет статический метод [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) класса `SlideUtil`. Он возвращает объекты `TextFrame` всей презентации и может включать текст из образцов слайдов. Следующий пример извлекает текст и связанные сведения о шрифте из презентации PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Извлечение текста из презентации PPT — Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как извлечь текст из PPT на Python" intro="Выполните следующие шаги, чтобы извлечь текст из файла PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте файл PPT с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `SlideUtil.get_all_text_frames` и укажите, нужно ли включать образцы слайдов.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите возвращённые объекты `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите коллекцию `paragraphs` каждой текстовой рамки.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите коллекцию `portions` каждого абзаца.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Прочитайте `text` и свойства форматирования текущего фрагмента.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Создано на основе Aspose.Slides" title="Извлекайте текст и изображения онлайн" description="Бесплатное приложение Aspose.Slides Parser создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Parser" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides читает ваши файлы, ещё до написания кода.
- Загрузите файл PPT и получите его текст и изображения.
- Скачайте всё одним ZIP-архивом.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для разбора" subTitle="С помощью Python можно также извлекать текст из других поддерживаемых форматов презентаций." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
