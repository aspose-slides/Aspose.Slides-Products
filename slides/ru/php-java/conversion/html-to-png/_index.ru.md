---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование HTML в PNG в PHP
url: /ru/php-java/conversion/html-to-png/
keywords: HTML в PNG, преобразовать HTML в PNG, PHP API, библиотеку PHP, HTML, PNG
description: Преобразование HTML в PNG в PHP. Используйте PowerPoint PHP API для преобразования файлов HTML в PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование HTML в PNG в PHP" h2="Мощная PHP-библиотека PowerPoint, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование HTML в PNG с помощью PHP" variant="code" %}}

Чтобы преобразовать HTML в PNG, вам нужно будет создать презентацию из файла HTML и сохранить его как PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-код для преобразования HTML в PNG" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
        
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename = 'file.html';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $pres->getSlides()->addFromHtml($contents);        
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
    }        
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование HTML в PNG в PHP" %}}

[**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/) — мощная библиотека PHP для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования HTML в PNG. Используя **Aspose.Slides for PHP через Java**, любой разработчик или приложение может преобразовать файлы HTML в PNG всего несколькими строками кода PHP.

Как современный API обработки документов, Aspose.Slides для PHP быстро экспортирует файлы HTML в форматы файлов PNG. Библиотека Aspose PowerPoint позволяет конвертировать HTML в PNG и многие другие форматы файлов.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать HTML в PNG с помощью Aspose.Slides for PHP API" intro="Это шаги для преобразования HTML в PNG в PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы HTML в PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Создано на основе Aspose.Slides" title="Конвертировать HTML в PNG онлайн" description="Бесплатное приложение Aspose.Slides Conversion создано на основе [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ru/php-java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами HTML." button="Открыть Aspose.Slides Conversion" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" upload="Перетащите или загрузите файл" saveAs="Сохранить как" convert="Конвертировать" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides конвертирует файлы, прежде чем писать код.
- Загрузите файлы HTML и сохраните их в PNG.
- Скачайте результат или конвертируйте другие файлы.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Конвертировать HTML в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать HTML и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
