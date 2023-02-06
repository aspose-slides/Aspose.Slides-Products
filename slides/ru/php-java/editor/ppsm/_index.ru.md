---
title: Изменить PPSM в PHP
url: /ru/php-java/editor/ppsm/
keywords: Редактировать PPSM, Редактировать PowerPoint, PPSM, PowerPoint, API PHP, библиотеку PHP
description: Отредактируйте PPSM в PHP. Используйте API библиотеки PHP для редактирования файлов PPSM
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Изменить PPSM в PHP" h2="Высокоскоростная и кроссплатформенная библиотека PHP для редактирования PPSM с использованием кода PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Отредактируйте PPSM с помощью Aspose.Slides" %}}

[**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/) — мощная PHP-библиотека для быстрого и простого редактирования презентаций. Он предоставляет пользователям широкий набор функций, помогающих создавать профессионально выглядящие слайды в кратчайшие сроки. С помощью Aspose пользователи могут редактировать текст, добавлять изображения, анимацию и переходы в свою презентацию, а также применять различные параметры форматирования, такие как тип шрифта и выбор цвета. Кроме того, библиотека предлагает поддержку как файлов PowerPoint (PPT), так и форматов презентаций OpenOffice (ODP), что упрощает обмен презентациями на разных платформах без каких-либо проблем с совместимостью. Используя возможности библиотеки Aspose при создании или редактировании вашей следующей презентации, вы будете уверены, что ваши слайды каждый раз будут выглядеть великолепно!
Вы можете редактировать файл PPSM, добавляя в него новую строку текста. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Изменить PPSM в PHP" %}}
Используя [**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/), вы можете добавить новую строку текста в документ PPSM всего одним несколько строк кода.

{{% blocks/products/pf/agp/code-block title="PHP-код для редактирования PPSM" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsm");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.ppsm", SaveFormat::Ppsm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как редактировать PPSM в PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для PHP через Java**. См. [**Установка**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте библиотеку в качестве ссылки в свой проект.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите презентацию PPSM, которую хотите отредактировать.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте новую строку текста.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните измененный файл.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Редактировать другие файлы" subTitle="Вы также можете редактировать файлы в других форматах" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}