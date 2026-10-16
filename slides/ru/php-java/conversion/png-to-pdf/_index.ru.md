---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PNG в PDF в PHP
url: /ru/php-java/conversion/png-to-pdf/
keywords: PNG в PDF, преобразовать PNG в PDF, PHP API, библиотеку PHP, PNG, PDF
description: Преобразование PNG в PDF в PHP. Используйте PowerPoint PHP API для преобразования файлов PNG в PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PNG в PDF в PHP" h2="Мощная PHP-библиотека PowerPoint, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PNG в PDF с помощью PHP" variant="code" %}}

Чтобы преобразовать PNG в PDF, вам нужно будет создать презентацию из файла PNG и сохранить его как PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-код для преобразования PNG в PDF" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PNG в PDF в PHP" %}}

[**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/) — мощная библиотека PHP для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования PNG в PDF. Используя **Aspose.Slides for PHP через Java**, любой разработчик или приложение может преобразовать файлы PNG в PDF всего несколькими строками кода PHP.

Как современный API обработки документов, Aspose.Slides для PHP быстро экспортирует файлы PNG в форматы файлов PDF. Библиотека Aspose PowerPoint позволяет конвертировать PNG в PDF и многие другие форматы файлов.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать PNG в PDF с помощью Aspose.Slides for PHP API" intro="Это шаги для преобразования PNG в PDF в PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы PNG в PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатный онлайн-конвертер"
  description="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Конвертировать PNG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PNG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
