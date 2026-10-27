---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование JPG в PDF в PHP
url: /ru/php-java/conversion/jpg-to-pdf/
keywords: JPG в PDF, преобразовать JPG в PDF, PHP API, библиотеку PHP, JPG, PDF
description: Преобразование JPG в PDF в PHP. Используйте PowerPoint PHP API для преобразования файлов JPG в PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование JPG в PDF в PHP" h2="Мощная PHP-библиотека PowerPoint, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование JPG в PDF с помощью PHP" variant="code" %}}

Чтобы преобразовать JPG в PDF, вам нужно будет создать презентацию из файла JPG и сохранить его как PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-код для преобразования JPG в PDF" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование JPG в PDF в PHP" %}}

[**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/) — мощная библиотека PHP для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования JPG в PDF. Используя **Aspose.Slides for PHP через Java**, любой разработчик или приложение может преобразовать файлы JPG в PDF всего несколькими строками кода PHP.

Как современный API обработки документов, Aspose.Slides для PHP быстро экспортирует файлы JPG в форматы файлов PDF. Библиотека Aspose PowerPoint позволяет конвертировать JPG в PDF и многие другие форматы файлов.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать JPG в PDF с помощью Aspose.Slides for PHP API" intro="Это шаги для преобразования JPG в PDF в PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы JPG в PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Создано на основе Aspose.Slides" title="Конвертировать JPG в PDF онлайн" description="Бесплатное приложение Aspose.Slides Conversion создано на основе [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ru/php-java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами JPG." button="Открыть Aspose.Slides Conversion" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" upload="Перетащите или загрузите файл" saveAs="Сохранить как" convert="Конвертировать" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides конвертирует файлы, прежде чем писать код.
- Загрузите файлы JPG и сохраните их в PDF.
- Скачайте результат или конвертируйте другие файлы.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Конвертировать JPG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать JPG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
