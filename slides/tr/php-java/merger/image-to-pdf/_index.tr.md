---
title: PHP'de Görüntüyü PDF'ye Birleştirme
url: /tr/php-java/merger/image-to-pdf/
keywords: Görüntüyü PDF'ye Dönüştürme, Görüntüyü PDF'ye Birleştirme, Görüntüyü PDF'ye Birleştirme, PDF, Görüntü, PHP API, PHP Kitaplığı
description: PHP'de Görüntüyü PDF'ye Birleştirme. Görüntü ve PDF'yi birleştirmek için PHP kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP'de Görüntüyü PDF'ye Birleştirme" h2="PHP kodunu kullanarak Görüntüyü PDF dosyalarıyla birleştirmek için yüksek hızlı ve platformlar arası PHP kitaplığı" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak Görüntüyü PDF'ye Birleştirme" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunumlar, PDF'ler oluşturmak, dönüştürmek, birleştirmek ve değiştirmek için kullanılan güçlü bir PHP kitaplığıdır. görüntüler ve diğer dosyalar. Görüntüyü PDF'de birleştirdiğinizde, tek bir PDF dosyası elde etmek için görüntüleri etkili bir şekilde birleştirmiş olursunuz.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PHP'de Görüntüyü PDF'ye Birleştirme" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) kullanarak, sadece birkaç satır kodla görseli PDF ile hızlı bir şekilde birleştirebilirsiniz

{{% blocks/products/pf/agp/code-block title="Görüntüyü PDF'ye birleştirmek için PHP kodu" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename1 = 'image1.png';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }

    $filename2 = 'image1.png';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $image1 = $pres->getImages()->addImage($contents1);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 0, 0, 360, 540, $image1);
    
    $image2 = $pres->getImages()->addImage($contents2);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 360, 0, 360, 540, $image2);

    $pres->save("merged-pdf.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PHP'de Görüntüyü PDF'ye nasıl birleştirirsiniz?" >}}


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
Birleştirmek istediğiniz görüntüleri resim çerçeveleri olarak yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan PDF'yi kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDF Dosyalarını Çevrimiçi Birleştirme" sectionDescription="[Python'da PDF Nasıl Birleştirilir](https://products.aspose.com/slides/tr/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları birleştir" subTitle="Tek bir dosya elde etmek için diğer formatlardaki dosyaları da birleştirebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}