---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование FODP в BMP в PHP
weight: 10
url: /ru/php-java/conversion/fodp-to-bmp/ 
keywords: "Convert, PowerPoint, FODP, BMP, Presentation, PHP"
description: Пример кода для преобразования FODP в BMP PHP. Используйте PowerPoint PHP API для пакетного преобразования файлов FODP в файлы BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование FODP в BMP в PHP" h2="Мощная PHP-библиотека PowerPoint для преобразования FODP в BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование FODP в BMP в PHP" %}}

Нужно программно преобразовать файлы FODP в BMP? Используя [*Aspose.Slides для PHP через Java*](https://products.aspose.com/slides/ru/php-java/), любой разработчик может преобразовать формат FODP в формат BMP всего несколькими строками кода PHP. .

Как современный API обработки презентаций, Aspose.Slides для PHP быстро создает BMP из FODP. Проверьте качество преобразования FODP в BMP прямо в вашем [браузере](https://products.aspose.app/slides/conversion). Библиотека Aspose PowerPoint PPTX позволяет конвертировать файлы FODP во многие популярные форматы.

Вы можете установить библиотеку из [Composer](https://packagist.org/packages/aspose/slides), используя следующую команду:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Консоль/терминал" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Сохранить FODP как BMP в PHP" %}}

Используйте бесплатное приложение, чтобы увидеть демонстрацию процесса преобразования FODP в BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Этот пример кода показывает преобразование FODP в BMP PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".bmp");
        $imageio->write($bmp, "BMP", $javafile);
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

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать FODP в BMP в PHP" intro="Это шаги для преобразования файла FODP в BMP с помощью PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл FODP с экземпляром класса Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.BMP в качестве параметров.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Файл FODP будет сохранен по указанному пути{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Системные Требования" intro="Перед запуском исходного кода примера преобразования PHP убедитесь, что выполнены следующие предварительные условия." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите PHP 7, добавьте путь к PHP в системную переменную `PATH` и установите для `allow_url_include` значение `On` в файле `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите JRE. 8. Установите переменную среды `JAVA_HOME` в качестве пути к месту установки JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите Apache Tomcat 8.0 (см. [подробнее](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert FODP to BMP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать FODP во многие другие форматы файлов. Смотрите другие поддерживаемые преобразования ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Графический формат обмена" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Язык гипертекстовой разметки" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Изображение в формате JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="Формат презентации OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="Стандартный формат OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Портативный формат документа" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Портативная сетевая графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Файл презентации с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Формат презентации Open XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Масштабируемая векторная графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF-формат" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Формат изображения с тегами" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
