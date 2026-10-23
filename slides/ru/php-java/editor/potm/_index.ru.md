---
lastmod: 2023-02-06
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Изменить POTM в PHP
url: /ru/php-java/editor/potm/
keywords: Редактировать POTM, Редактировать PowerPoint, POTM, PowerPoint, API PHP, библиотеку PHP
description: Отредактируйте POTM в PHP. Используйте API библиотеки PHP для редактирования файлов POTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Изменить POTM в PHP" h2="Высокоскоростная и кроссплатформенная библиотека PHP для редактирования POTM с использованием кода PHP" related="FODP,HTML,ODP,OTP,PDF,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Изменить POTM в PHP" variant="code" %}}

Используя [**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/), вы можете добавить новую строку текста в документ POTM всего одним несколько строк кода.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-код для редактирования POTM" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.potm", SaveFormat::Potm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Отредактируйте POTM с помощью Aspose.Slides" %}}

[**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/) — мощная PHP-библиотека для быстрого и простого редактирования презентаций. Он предоставляет пользователям широкий набор функций, помогающих создавать профессионально выглядящие слайды в кратчайшие сроки. С помощью Aspose пользователи могут редактировать текст, добавлять изображения, анимацию и переходы в свою презентацию, а также применять различные параметры форматирования, такие как тип шрифта и выбор цвета. Кроме того, библиотека предлагает поддержку как файлов PowerPoint (PPT), так и форматов презентаций OpenOffice (ODP), что упрощает обмен презентациями на разных платформах без каких-либо проблем с совместимостью. Используя возможности библиотеки Aspose при создании или редактировании вашей следующей презентации, вы будете уверены, что ваши слайды каждый раз будут выглядеть великолепно!
Вы можете редактировать файл POTM, добавляя в него новую строку текста.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как редактировать POTM в PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите **Aspose.Slides для PHP через Java**. См. [**Установка**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте библиотеку в качестве ссылки в свой проект.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите презентацию POTM, которую хотите отредактировать.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте новую строку текста.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните измененный файл.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Создано на основе Aspose.Slides" title="Редактируйте файлы PPTX онлайн" description="Бесплатное приложение Aspose.Slides Editor создано на основе [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ru/php-java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Editor" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides обрабатывает ваши файлы, ещё до написания кода.
- Загрузите файлы PPTX и сразу редактируйте их.
- Сохраните и скачайте отредактированный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Редактировать другие файлы" subTitle="Вы также можете редактировать файлы в других форматах" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/php-java/editor/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
