---
title: Слияние файлов HTML в PHP
url: /ru/php-java/merger/html-to-html/
keywords: Объединение HTML, HTML в HTML, объединение HTML, объединение HTML, API PHP, библиотека PHP
description: Слияние HTML с HTML в PHP. Используйте API библиотеки PHP для объединения файлов HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Объединить HTML в PHP" h2="Высокоскоростная и кроссплатформенная библиотека PHP для слияния файлов HTML с использованием кода PHP." >}}

{{% blocks/products/pf/feature-page-section h2="Слияние HTML с HTML с помощью Aspose.Slides" %}}

[**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/) — это мощная библиотека PHP, используемая для создания, преобразования, объединения и управления презентациями, HTML-файлами. , и другие документы. Когда вы объединяете HTML в HTML, вы фактически объединяете содержимое двух документов для получения одного HTML-файла. Aspose.Slides позволяет объединять HTML-документы различными способами. Вы можете объединить HTML со всеми их текстами, форматированием, стилями и т. д.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Слияние HTML с HTML в PHP" %}}
Используя [**Aspose.Slides для PHP через Java**](https://products.aspose.com/slides/ru/php-java/), вы можете быстро объединять HTML-файлы всего несколькими строками кода.

{{% blocks/products/pf/agp/code-block title="PHP-код для слияния HTML с HTML" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename1 = 'file1.html';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }
    
    $pres->getSlides()->addFromHtml($contents1);
    
    $filename2 = 'file2.html';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $pres->getSlides()->addFromHtml($contents2);

    $pres->save("merged-html.html", SaveFormat::Html5);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как объединить HTML в PHP" >}}


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
Загрузите файлы HTML, которые вы хотите объединить.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните полученный HTML-документ.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Объединить PDF-файлы онлайн" sectionDescription="[Как объединить PDF в Python](https://products.aspose.com/slides/ru/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Объединить другие файлы" subTitle="Вы также можете комбинировать файлы в других форматах, чтобы получить один файл." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}