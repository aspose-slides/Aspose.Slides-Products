---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Извлечение текста из файлов ODP на Python
url: /ru/python-net/parser/odp/
description: Извлекайте текст и сведения о форматировании текста из презентаций ODP на Python.
keywords: разбор ODP на Python, парсер ODP Python, извлечение данных из ODP на Python, извлечение текста из ODP на Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Извлечение текста из презентаций ODP на Python" h2="Создавайте приложения на Python, которые с помощью Aspose.Slides извлекают текст и сведения о форматировании из презентаций OpenDocument." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Извлечение текста из презентации ODP на Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/ru/python-net/) предоставляет статический метод [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) класса `SlideUtil`. Он возвращает объекты `TextFrame` всей презентации и может включать текст из образцов слайдов. Следующий пример извлекает текст и связанные сведения о шрифте из презентации ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Извлечение текста из презентации ODP — Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как извлечь текст из ODP на Python" intro="Выполните следующие шаги, чтобы извлечь текст из файла ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте файл ODP с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `SlideUtil.get_all_text_frames` и укажите, нужно ли включать образцы слайдов.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите возвращённые объекты `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите коллекцию `paragraphs` каждой текстовой рамки.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите коллекцию `portions` каждого абзаца.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Прочитайте `text` и свойства форматирования текущего фрагмента.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Создано на основе Aspose.Slides" title="Извлекайте текст и изображения онлайн" description="Бесплатное приложение Aspose.Slides Parser создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами ODP." button="Открыть Aspose.Slides Parser" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides читает ваши файлы, ещё до написания кода.
- Загрузите файл ODP и получите его текст и изображения.
- Скачайте всё одним ZIP-архивом.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для разбора" subTitle="С помощью Python можно также извлекать текст из других поддерживаемых форматов презентаций." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
