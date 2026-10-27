---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Удаление аннотаций из PPTX с помощью C++
url: /ru/cpp/annotation/pptx/ 
description: Исходный код C++ для удаления аннотаций из презентаций PPTX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Удаление комментариев и авторов комментариев из PPTX на C++" h2="Создавайте приложения C++, которые управляют комментариями и авторами в файлах презентаций с помощью серверных API." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Удаление комментариев из PPTX на C++" variant="code" %}}

С помощью [Aspose.Slides for C++](/slides/ru/cpp/) можно удалить комментарии и авторов комментариев из презентаций PPTX. В примере ниже очищаются комментарии каждого автора из `get_CommentAuthors`, а затем коллекция авторов комментариев.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Удаление аннотаций из PPTX – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.pptx");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как удалить комментарии из PPTX на C++" intro="Выполните следующие шаги, чтобы удалить комментарии и авторов комментариев из презентации PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите Aspose.Slides for C++. См. [Установка](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите авторов комментариев из `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Очистите комментарии каждого автора с помощью `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Очистите коллекцию авторов комментариев.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните обновлённую презентацию с `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Создано на основе Aspose.Slides" title="Удаление комментариев из PPTX онлайн" description="Бесплатное приложение Aspose.Slides Annotation создано на основе [Aspose.Slides for C++](https://products.aspose.com/slides/ru/cpp/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Annotation" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides удаляет комментарии, ещё до написания кода.
- Удалите все комментарии из файла PPTX.
- Скачайте очищенный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для аннотаций" subTitle="С помощью C++ можно также удалять аннотации из других форматов." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
