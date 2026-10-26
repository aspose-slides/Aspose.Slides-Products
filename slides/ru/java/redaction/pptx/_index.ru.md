---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Скрытие данных в файлах презентаций PPTX с помощью Java
url: /ru/java/redaction/pptx/
description: Находите и заменяйте текст в презентациях PPTX на Java с помощью Aspose.Slides for Java.
keywords: скрыть данные в PPTX, найти и заменить текст в PPTX, обновить презентацию PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Скрытие данных в PPTX с помощью Java" h2="Создавайте приложения Java, которые находят и заменяют текст в файлах презентаций с помощью серверных API." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Скрытие данных в презентации PPTX на Java" variant="code" %}}

С [Aspose.Slides for Java](/slides/ru/java/) можно находить и заменять текст в презентациях PPTX. Используйте метод `SlideUtil.findAndReplaceText`, чтобы выполнить поиск по презентации и заменить совпадающий текст новым значением.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Скрытие данных в презентации PPTX с помощью Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как скрыть данные в PPTX на Java" intro="Выполните следующие шаги, чтобы скрыть данные в презентации PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `SlideUtil.findAndReplaceText`, чтобы найти и заменить текст.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните обновлённую презентацию с `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Создано на основе Aspose.Slides" title="Скрытие данных в файлах PPTX онлайн" description="Бесплатное приложение Aspose.Slides Redaction создано на основе [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Redaction" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит и заменяет текст, ещё до написания кода.
- Находите и заменяйте текст в файле PPTX, в том числе с помощью регулярных выражений.
- Скачайте обработанный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для скрытия данных" subTitle="С помощью Java можно также скрывать данные в следующих форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
