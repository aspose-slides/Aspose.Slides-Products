---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Поиск текста в презентациях ODP с помощью Python
url: /ru/python-net/search/odp/
description: Ищите текст в презентациях ODP с помощью Python и Aspose.Slides.
keywords: поиск текста в ODP, найти слова в ODP, поиск в презентации ODP на Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Поиск текста в презентациях ODP с помощью Python" h2="Создавайте приложения Python, которые находят текст в презентациях OpenDocument с помощью Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Поиск текста в презентации ODP с помощью Python" variant="code" %}}

С [Aspose.Slides for Python via .NET](/slides/ru/python-net/) можно с помощью [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) находить на каждом слайде текстовые рамки, содержащие заданную строку.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Поиск текста в презентации ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как найти текст в ODP с помощью Python" intro="Выполните следующие шаги, чтобы найти текст в презентации ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте файл ODP с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите слайды и для каждого вызовите [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Прочитайте свойство `text` каждой найденной текстовой рамки.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Создано на основе Aspose.Slides" title="Поиск текста в файлах ODP онлайн" description="Бесплатное приложение Aspose.Slides Search создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами ODP." button="Открыть Aspose.Slides Search" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит текст, ещё до написания кода.
- Ищите в файле ODP обычный текст или регулярные выражения.
- Скачайте найденные совпадения в виде текстового файла.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для поиска" subTitle="С помощью Python можно искать текст и в других поддерживаемых форматах презентаций." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
