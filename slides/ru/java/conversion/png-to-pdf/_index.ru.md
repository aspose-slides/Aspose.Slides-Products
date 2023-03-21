---
title: Преобразование PNG в PDF в Java
url: /ru/java/conversion/png-to-pdf/
keywords: PNG в PDF, преобразовать PNG в PDF, API Java, библиотеку Java, PNG, PDF
description: Преобразование PNG в PDF в Java. Используйте API библиотеки Java для преобразования файлов PNG в файлы PDF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование PNG в PDF в Java" h2="Высокоскоростная и кроссплатформенная библиотека Java, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование PNG в PDF в Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/) — мощная библиотека Java для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования PNG в PDF. Используя **Aspose.Slides for Java**, любой разработчик или приложение может преобразовать файлы PNG в PDF всего несколькими строками кода Java.

Как современный API обработки документов, Aspose.Slides для Java быстро экспортирует файлы PNG в форматы файлов PDF. Библиотека Aspose PowerPoint позволяет конвертировать PNG в PDF и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PNG в PDF с помощью Java" %}}
Чтобы преобразовать PNG в PDF, вам нужно будет создать презентацию из файла PNG и сохранить его как PDF.

{{% blocks/products/pf/agp/code-block title="Код Java для преобразования PNG в PDF" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать PNG в PDF с помощью Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования PNG в PDF в Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для Java**](https://products.aspose.com/slides/ru/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы PNG в Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат как файл PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Бесплатный онлайн-конвертер" sectionDescription="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Конвертировать PNG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PNG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}