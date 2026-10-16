---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PPTX в Word на Java
url: /ru/java/conversion/pptx-to-word/
keywords: Преобразование PPTX в Word, PPTX в Word, PPTX в DOC, PowerPoint в Word, API Java, библиотека Java
description: Преобразование PPTX в Word на Java. Используйте API библиотеки Java для преобразования PowerPoint в Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PPTX в Word на Java" h2="Мощный кроссплатформенный API Java для преобразования PowerPoint в Word с использованием кода Java без использования Microsoft PowerPoint или Office." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PowerPoint в Word на Java" variant="code" %}}

Вы можете быстро преобразовать PPTX в Word, написав всего несколько строк кода.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код Java для преобразования PowerPoint в Word" >}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Конвертируйте PowerPoint в Word с помощью Aspose.Slides и Aspose.Words" %}}

[**Aspose.Slides для Java**](https://products.aspose.com/slides/ru/java/) и [**Aspose.Words для Java**](https://products.aspose.com/ words/java/) — это мощные библиотеки Java, используемые для управления и преобразования презентаций PowerPoint, документов Word и других файлов. Когда вы конвертируете PowerPoint в Word, вы, по сути, перемещаете содержимое слайдов презентации на страницы документа Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать PPTX в Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите **Aspose.Slides для Java** и **Aspose.Words для Java**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр класса Presentation и класса Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите презентацию PPTX, которую вы хотите преобразовать в Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создавайте изображения и тексты на основе содержимого слайдов.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните полученный документ Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатный онлайн-конвертер"
  description="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PowerPoint в файлы других форматов." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
