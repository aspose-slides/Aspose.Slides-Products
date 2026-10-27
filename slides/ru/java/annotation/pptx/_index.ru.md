---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 360
title: Удаление аннотаций из PPTX с помощью Java
url: /ru/java/annotation/pptx/ 
description: Удаляйте комментарии и авторов комментариев из презентаций PPTX на Java с помощью Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Удаление комментариев и авторов комментариев из PPTX на Java" h2="Используйте Aspose.Slides for Java, чтобы удалять комментарии и авторов комментариев из файлов презентаций." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Удаление комментариев из PPTX на Java" variant="code" %}}

Aspose.Slides for Java позволяет удалять комментарии и авторов комментариев из презентаций PPTX. Загрузите файл с помощью класса `Presentation`, переберите объекты `ICommentAuthor` из `getCommentAuthors`, очистите их комментарии и сохраните обновлённую презентацию.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Удаление аннотаций из PPTX – Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как удалить комментарии из PPTX на Java" intro="Выполните следующие шаги, чтобы удалить комментарии и авторов комментариев из презентации PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите Aspose.Slides for Java. См. [Установка](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Переберите объекты `ICommentAuthor` из `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Очистите комментарии каждого автора с помощью `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Очистите коллекцию авторов комментариев и сохраните обновлённый файл PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Создано на основе Aspose.Slides" title="Удаление комментариев из PPTX онлайн" description="Бесплатное приложение Aspose.Slides Annotation создано на основе [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Annotation" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides удаляет комментарии, ещё до написания кода.
- Удалите все комментарии из файла PPTX.
- Скачайте очищенный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для аннотаций" subTitle="С помощью Java можно также удалять аннотации из других форматов." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
