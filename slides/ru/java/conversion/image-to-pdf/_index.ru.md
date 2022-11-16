---
title: Преобразование Image в PDF в Java
url: /ru/java/conversion/image-to-pdf/
keywords: Image в PDF, преобразовать Image в PDF, API Java, библиотеку Java, Image, PDF
description: Преобразование Image в PDF в Java. Используйте API библиотеки Java для преобразования файлов Image в файлы PDF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование Image в PDF в Java" h2="Высокоскоростная и кроссплатформенная библиотека Java, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Image в PDF в Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/) — мощная библиотека Java для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования Image в PDF. Используя **Aspose.Slides for Java**, любой разработчик или приложение может преобразовать файлы Image в PDF всего несколькими строками кода Java.

Как современный API обработки документов, Aspose.Slides для Java быстро экспортирует файлы Image в форматы файлов PDF. Библиотека Aspose PowerPoint позволяет конвертировать Image в PDF и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Image в PDF с помощью Java" %}}
Чтобы преобразовать Image в PDF, вам нужно будет создать презентацию из файла Image и сохранить его как PDF.

{{% blocks/products/pf/agp/code-block title="Код Java для преобразования Image в PDF" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать Image в PDF с помощью Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования Image в PDF в Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source Image files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PDF file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Конвертировать Image в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать Image и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}