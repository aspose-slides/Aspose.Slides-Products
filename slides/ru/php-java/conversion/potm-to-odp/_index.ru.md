---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование POTM в ODP в PHP
weight: 1110
url: /ru/php-java/conversion/potm-to-odp/ 
keywords: "Convert, PowerPoint, POTM, ODP, Presentation, PHP"
description: Пример кода для преобразования POTM в ODP PHP. Используйте PowerPoint PHP API для пакетного преобразования файлов POTM в файлы ODP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование POTM в ODP в PHP" h2="Мощная PHP-библиотека PowerPoint для преобразования POTM в ODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование POTM в ODP в PHP" %}}

Нужно программно преобразовать файлы POTM в ODP? Используя [*Aspose.Slides для PHP через Java*](https://products.aspose.com/slides/ru/php-java/), любой разработчик может преобразовать формат POTM в формат ODP всего несколькими строками кода PHP. .

Как современный API обработки презентаций, Aspose.Slides для PHP быстро создает ODP из POTM. Проверьте качество преобразования POTM в ODP прямо в вашем [браузере](https://products.aspose.app/slides/conversion). Библиотека Aspose PowerPoint PPTX позволяет конвертировать файлы POTM во многие популярные форматы.

Вы можете установить библиотеку из [Composer](https://packagist.org/packages/aspose/slides), используя следующую команду:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Консоль/терминал" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Сохранить POTM как ODP в PHP" %}}

Используйте бесплатное приложение, чтобы увидеть демонстрацию процесса преобразования POTM в ODP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Этот пример кода показывает преобразование POTM в ODP PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
try
{
    $pres->save("output.odp", SaveFormat::Odp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать POTM в ODP в PHP" intro="Это шаги для преобразования файла POTM в ODP с помощью PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл POTM с экземпляром класса Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.ODP в качестве параметров.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Файл POTM будет сохранен по указанному пути{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Системные Требования" intro="Перед запуском исходного кода примера преобразования PHP убедитесь, что выполнены следующие предварительные условия." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите PHP 7, добавьте путь к PHP в системную переменную `PATH` и установите для `allow_url_include` значение `On` в файле `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите JRE. 8. Установите переменную среды `JAVA_HOME` в качестве пути к месту установки JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите Apache Tomcat 8.0 (см. [подробнее](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POTM to ODP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать POTM во многие другие форматы файлов. Смотрите другие поддерживаемые преобразования ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Растровое изображение" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="Плоская XML-презентация OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="Графический формат обмена" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="Язык гипертекстовой разметки" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="Изображение в формате JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="Стандартный формат OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Портативный формат документа" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="Портативная сетевая графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Файл презентации с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Формат презентации Open XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="Масштабируемая векторная графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF-формат" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Формат изображения с тегами" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
