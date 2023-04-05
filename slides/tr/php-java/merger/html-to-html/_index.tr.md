---
title: PHP'de HTML Dosyalarını Birleştirme
url: /tr/php-java/merger/html-to-html/
keywords: HTML'yi Birleştirme, HTML'den HTML'ye, HTML'ye Birleştirme, HTML'yi Birleştirme, PHP API, PHP Kitaplığı
description: PHP'de HTML'yi HTML ile birleştirin. HTML dosyalarını birleştirmek için PHP kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP'de HTML'yi birleştirme" h2="PHP kodunu kullanarak HTML dosyalarını birleştirmek için yüksek hızlı ve platformlar arası PHP kitaplığı" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak HTML'yi HTML ile birleştirin" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunumlar ve HTML dosyaları oluşturmak, dönüştürmek, birleştirmek ve değiştirmek için kullanılan güçlü bir PHP kitaplığıdır ve diğer belgeler. HTML'yi HTML'ye birleştirdiğinizde, tek bir HTML dosyası elde etmek için 2 belgenin içeriğini etkili bir şekilde birleştirmiş olursunuz. Aspose.Slides, HTML belgelerini farklı şekillerde birleştirmenizi sağlar. HTML'yi tüm metinleri, biçimlendirmeleri, stilleri vb. ile birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PHP'de HTML'yi HTML ile birleştirme" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) kullanarak, HTML dosyalarını yalnızca birkaç satır kodla hızlı bir şekilde birleştirebilirsiniz

{{% blocks/products/pf/agp/code-block title="HTML'yi HTML'ye birleştirmek için PHP kodu" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="PHP'de HTML nasıl birleştirilir" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for PHP'yi Java aracılığıyla** kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Birleştirmek istediğiniz HTML dosyalarını yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan HTML belgesini kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDF Dosyalarını Çevrimiçi Birleştirme" sectionDescription="[Python'da PDF Nasıl Birleştirilir](https://products.aspose.com/slides/tr/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları birleştir" subTitle="Tek bir dosya elde etmek için diğer formatlardaki dosyaları da birleştirebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}