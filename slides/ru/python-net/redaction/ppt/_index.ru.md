---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Скрытие текста в презентациях PPT с помощью Python
url: /ru/python-net/redaction/ppt/
description: Находите и заменяйте конфиденциальный текст в презентациях PPT с помощью Python.
keywords: скрыть данные в PPT, найти и заменить текст в PPT, обновить презентацию PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Скрытие текста в презентациях PPT с помощью Python" h2="Создавайте приложения Python, которые находят и заменяют конфиденциальный текст в презентациях с помощью Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Скрытие текста в презентации PPT с помощью Python" variant="code" %}}

С [Aspose.Slides for Python via .NET](/slides/ru/python-net/) можно заменить конфиденциальный текст во всей презентации PPT. Используйте `Presentation.replace_text` с `TextSearchOptions`, чтобы управлять поиском, а затем сохраните изменённую презентацию.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Скрытие текста в презентации PPT – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как скрыть текст в презентации PPT с помощью Python" intro="Выполните следующие шаги, чтобы заменить конфиденциальный текст в презентации PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте файл PPT с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Используйте [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) с `TextSearchOptions`, чтобы заменить нужный текст.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните изменённую презентацию с `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Создано на основе Aspose.Slides" title="Скрытие данных в файлах PPT онлайн" description="Бесплатное приложение Aspose.Slides Redaction создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Redaction" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит и заменяет текст, ещё до написания кода.
- Находите и заменяйте текст в файле PPT, в том числе с помощью регулярных выражений.
- Скачайте обработанный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для скрытия данных" subTitle="С помощью Python можно скрывать текст и в других поддерживаемых форматах презентаций." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
