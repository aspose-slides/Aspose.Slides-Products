---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Поиск текста в файлах презентаций PPTX с помощью Java
url: /ru/java/search/pptx/
description: Ищите текст в презентациях PPTX на Java с помощью Aspose.Slides for Java.
keywords: поиск слов в PPTX, поиск текста в PPTX, поиск по тексту презентации PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Поиск текста в PPTX с помощью Java" h2="Создавайте приложения Java, которые ищут текст в файлах презентаций с помощью серверных API." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Поиск текста в презентации PPTX на Java" variant="code" %}}

С [Aspose.Slides for Java](/slides/ru/java/) можно искать текст в презентациях PPTX. Соберите текстовые рамки методом `SlideUtil.getAllTextBoxes`, а затем проверьте объекты `ITextFrame`, `IParagraph` и `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Поиск текста в презентации PPTX с помощью Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как найти текст в PPTX на Java" intro="Выполните следующие шаги, чтобы найти текст в презентации PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `SlideUtil.getAllTextBoxes`, чтобы собрать текстовые рамки каждого слайда.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Проверьте объекты `ITextFrame`, `IParagraph` и `IPortion`, чтобы найти совпадающий текст.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Создано на основе Aspose.Slides" title="Поиск текста в файлах PPTX онлайн" description="Бесплатное приложение Aspose.Slides Search создано на основе [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Search" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит текст, ещё до написания кода.
- Ищите в файле PPTX обычный текст или регулярные выражения.
- Скачайте найденные совпадения в виде текстового файла.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для поиска" subTitle="С помощью Java можно также искать текст в следующих форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
