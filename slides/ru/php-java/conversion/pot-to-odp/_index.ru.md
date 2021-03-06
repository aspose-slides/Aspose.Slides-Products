---
title: Преобразование POT в ODP в PHP
weight: 900
url: /ru/php-java/conversion/pot-to-odp/ 
keywords: "Convert, PowerPoint, POT, ODP, Presentation, PHP"
description: Пример кода для преобразования POT в ODP PHP. Используйте PowerPoint PHP API для пакетного преобразования файлов POT в файлы ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование POT в ODP в PHP" h2="Мощная PHP-библиотека PowerPoint для преобразования POT в ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Преобразование POT в ODP в PHP" %}}

Нужно программно преобразовать файлы POT в ODP? Используя [*Aspose.Slides для PHP через Java*](https://products.aspose.com/slides/ru/php-java/), любой разработчик может преобразовать формат POT в формат ODP всего несколькими строками кода PHP. .

Как современный API обработки презентаций, Aspose.Slides для PHP быстро создает ODP из POT. Проверьте качество преобразования POT в ODP прямо в вашем [браузере](https://products.aspose.app/slides/conversion). Библиотека Aspose PowerPoint PPTX позволяет конвертировать файлы POT во многие популярные форматы.

Вы можете установить библиотеку из [Composer](https://packagist.org/packages/aspose/slides), используя следующую команду:

{{% blocks/products/pf/agp/code-block title="Консоль/терминал" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Как преобразовать POT в ODP в PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования файла POT в ODP с помощью PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите файл POT с экземпляром класса Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.ODP в качестве параметров.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Файл POT будет сохранен по указанному пути
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском исходного кода примера преобразования PHP убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

1. Установите PHP 7, добавьте путь к PHP в системную переменную `PATH` и установите для `allow_url_include` значение `On` в файле `php.ini`.
1. Установите JRE. 8. Установите переменную среды `JAVA_HOME` в качестве пути к месту установки JRE.
1. Установите Apache Tomcat 8.0 (см. [подробнее](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Этот пример кода показывает преобразование POT в ODP PHP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
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
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Сохранить POT как ODP в PHP" %}}
Используйте бесплатное приложение, чтобы увидеть демонстрацию процесса преобразования POT в ODP. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert POT to ODP" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать POT во многие другие форматы файлов. Смотрите другие поддерживаемые преобразования ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-bmp/" name="POT TO BMP" description="Растровое изображение" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-fodp/" name="POT TO FODP" description="Плоская XML-презентация OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-gif/" name="POT TO GIF" description="Графический формат обмена" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-html/" name="POT TO HTML" description="Язык гипертекстовой разметки" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-jpg/" name="POT TO JPG" description="Изображение в формате JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-otp/" name="POT TO OTP" description="Стандартный формат OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-pdf/" name="POT TO PDF" description="Портативный формат документа" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-png/" name="POT TO PNG" description="Портативная сетевая графика" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-potm/" name="POT TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-potx/" name="POT TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-pps/" name="POT TO PPS" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Слайд-шоу PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-pptm/" name="POT TO PPTM" description="Файл презентации с поддержкой макросов" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-pptx/" name="POT TO PPTX" description="Формат презентации Open XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-svg/" name="POT TO SVG" description="Масштабируемая векторная графика" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-swf/" name="POT TO SWF" description="SWF-формат" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-tiff/" name="POT TO TIFF" description="Формат изображения с тегами" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/conversion/pot-to-xps/" name="POT TO XPS" description="Спецификации XML-бумаги" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}