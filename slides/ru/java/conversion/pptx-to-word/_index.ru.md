---
title: Преобразование PPTX в Word на Java
url: /ru/java/conversion/pptx-to-word/
keywords: Преобразование PPTX в Word, PPTX в Word, PPTX в DOC, PowerPoint в Word, API Java, библиотека Java
description: Преобразование PPTX в Word на Java. Используйте API библиотеки Java для преобразования PowerPoint в Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование PPTX в Word на Java" h2="Мощный кроссплатформенный API Java для преобразования PowerPoint в Word с использованием кода Java без использования Microsoft PowerPoint или Office." >}}

{{% blocks/products/pf/feature-page-section h2="Конвертируйте PowerPoint в Word с помощью Aspose.Slides и Aspose.Words" %}}

[**Aspose.Slides для Java**](https://products.aspose.com/slides/ru/java/) и [**Aspose.Words для Java**](https://products.aspose.com/ words/java/) — это мощные библиотеки Java, используемые для управления и преобразования презентаций PowerPoint, документов Word и других файлов. Когда вы конвертируете PowerPoint в Word, вы, по сути, перемещаете содержимое слайдов презентации на страницы документа Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Преобразование PowerPoint в Word на Java" %}}
Вы можете быстро преобразовать PPTX в Word, написав всего несколько строк кода.

{{% blocks/products/pf/agp/code-block title="Код Java для преобразования PowerPoint в Word" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как преобразовать PPTX в Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для Java** и **Aspose.Words для Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation и класса Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите презентацию PPTX, которую вы хотите преобразовать в Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создавайте изображения и тексты на основе содержимого слайдов.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните полученный документ Word.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Бесплатный онлайн-конвертер" sectionDescription="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PowerPoint в файлы других форматов." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}