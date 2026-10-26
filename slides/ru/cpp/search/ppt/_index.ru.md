---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Поиск текста в презентациях PPT с помощью C++
url: /ru/cpp/search/ppt/
description: Ищите текст в презентациях PPT на C++. Используйте Aspose.Slides for C++, чтобы находить текст в файлах презентаций.
keywords: поиск слов в PPT, найти текст в PPT, поиск по тексту презентации PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Поиск текста в PPT с помощью C++" h2="Используйте Aspose.Slides for C++, чтобы находить текст в файлах презентаций без Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Поиск текста в презентации PPT на C++" variant="code" %}}

Aspose.Slides for C++ позволяет искать текст в презентациях PPT. Соберите текстовые рамки слайда с помощью `SlideUtil::GetAllTextBoxes`, а затем проверьте, содержит ли их текст нужную фразу.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Поиск текста в презентации PPT с помощью C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как найти текст в PPT на C++" intro="Выполните следующие шаги, чтобы найти текст в презентации PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPT с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Получите нужный слайд через `Presentation::get_Slides` и его текстовые рамки с помощью [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Проверьте, содержит ли текст каждой рамки нужную фразу.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Создано на основе Aspose.Slides" title="Поиск текста в файлах PPT онлайн" description="Бесплатное приложение Aspose.Slides Search создано на основе [Aspose.Slides for C++](https://products.aspose.com/slides/ru/cpp/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Search" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит текст, ещё до написания кода.
- Ищите в файле PPT обычный текст или регулярные выражения.
- Скачайте найденные совпадения в виде текстового файла.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для поиска" subTitle="С помощью C++ можно также искать текст в следующих форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
