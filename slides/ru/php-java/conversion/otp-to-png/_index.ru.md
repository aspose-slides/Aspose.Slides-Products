---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование OTP в PNG в PHP
weight: 500
url: /ru/php-java/conversion/otp-to-png/ 
keywords: "Convert, PowerPoint, OTP, PNG, Presentation, PHP"
description: Пример кода для преобразования OTP в PNG PHP. Используйте PowerPoint PHP API для пакетного преобразования файлов OTP в файлы PNG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование OTP в PNG в PHP" h2="Мощная PHP-библиотека PowerPoint для преобразования OTP в PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование OTP в PNG в PHP" %}}

Нужно программно преобразовать файлы OTP в PNG? Используя [*Aspose.Slides для PHP через Java*](https://products.aspose.com/slides/ru/php-java/), любой разработчик может преобразовать формат OTP в формат PNG всего несколькими строками кода PHP. .

Как современный API обработки презентаций, Aspose.Slides для PHP быстро создает PNG из OTP. Проверьте качество преобразования OTP в PNG прямо в вашем [браузере](https://products.aspose.app/slides/conversion/ppt-to-png). Библиотека Aspose PowerPoint PPTX позволяет конвертировать файлы OTP во многие популярные форматы.

Вы можете установить библиотеку из [Composer](https://packagist.org/packages/aspose/slides), используя следующую команду:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Консоль/терминал" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Сохранить OTP как PNG в PHP" %}}

Используйте бесплатное приложение, чтобы увидеть демонстрацию процесса преобразования OTP в PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Этот пример кода показывает преобразование OTP в PNG PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
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

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать OTP в PNG в PHP" intro="Это шаги для преобразования файла OTP в PNG с помощью PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл OTP с экземпляром класса Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.PNG в качестве параметров.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Файл OTP будет сохранен по указанному пути{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Системные Требования" intro="Перед запуском исходного кода примера преобразования PHP убедитесь, что выполнены следующие предварительные условия." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите PHP 7, добавьте путь к PHP в системную переменную `PATH` и установите для `allow_url_include` значение `On` в файле `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите JRE. 8. Установите переменную среды `JAVA_HOME` в качестве пути к месту установки JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите Apache Tomcat 8.0 (см. [подробнее](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert OTP to PNG"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать OTP во многие другие форматы файлов. Смотрите другие поддерживаемые преобразования ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-bmp/" name="OTP TO BMP" description="Растровое изображение" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-fodp/" name="OTP TO FODP" description="Плоская XML-презентация OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="Графический формат обмена" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-html/" name="OTP TO HTML" description="Язык гипертекстовой разметки" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="Изображение в формате JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="Формат презентации OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="Портативный формат документа" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-pps/" name="OTP TO PPS" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Файл презентации с поддержкой макросов" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Формат презентации Open XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="Масштабируемая векторная графика" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF-формат" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Формат изображения с тегами" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
