---
title: Преобразование HTML в PDF в Java
url: /ru/java/conversion/html-to-pdf/
keywords: HTML в PDF, преобразовать HTML в PDF, API Java, библиотеку Java, HTML, PDF
description: Преобразование HTML в PDF в Java. Используйте API библиотеки Java для преобразования файлов HTML в файлы PDF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование HTML в PDF в Java" h2="Высокоскоростная и кроссплатформенная библиотека Java, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование HTML в PDF в Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/) — мощная библиотека Java для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования HTML в PDF. Используя **Aspose.Slides for Java**, любой разработчик или приложение может преобразовать файлы HTML в PDF всего несколькими строками кода Java.

Как современный API обработки документов, Aspose.Slides для Java быстро экспортирует файлы HTML в форматы файлов PDF. Библиотека Aspose PowerPoint позволяет конвертировать HTML в PDF и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование HTML в PDF с помощью Java" %}}
Чтобы преобразовать HTML в PDF, вам нужно будет создать презентацию из файла HTML и сохранить его как PDF.

{{% blocks/products/pf/agp/code-block title="Код Java для преобразования HTML в PDF" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать HTML в PDF с помощью Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования HTML в PDF в Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source HTML files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PDF file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Конвертировать HTML в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать HTML и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}