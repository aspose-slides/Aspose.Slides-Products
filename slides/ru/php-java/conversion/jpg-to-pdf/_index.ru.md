---
title: Преобразование JPG в PDF в PHP
url: /ru/php-java/conversion/jpg-to-pdf/
keywords: JPG в PDF, преобразовать JPG в PDF, PHP API, библиотеку PHP, JPG, PDF
description: Преобразование JPG в PDF в PHP. Используйте PowerPoint PHP API для преобразования файлов JPG в PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование JPG в PDF в PHP" h2="Мощная PHP-библиотека PowerPoint, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование JPG в PDF в PHP" %}}

[**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/) — мощная библиотека PHP для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования JPG в PDF. Используя **Aspose.Slides for PHP через Java**, любой разработчик или приложение может преобразовать файлы JPG в PDF всего несколькими строками кода PHP.

Как современный API обработки документов, Aspose.Slides для PHP быстро экспортирует файлы JPG в форматы файлов PDF. Библиотека Aspose PowerPoint позволяет конвертировать JPG в PDF и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование JPG в PDF с помощью PHP" %}}
Чтобы преобразовать JPG в PDF, вам нужно будет создать презентацию из файла JPG и сохранить его как PDF.

{{% blocks/products/pf/agp/code-block title="PHP-код для преобразования JPG в PDF" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать JPG в PDF с помощью Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования JPG в PDF в PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы JPG в PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат как файл PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Бесплатный онлайн-конвертер" sectionDescription="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Конвертировать JPG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать JPG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}