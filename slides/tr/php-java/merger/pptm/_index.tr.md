---
title: PPTM Dosyalarını PHP Kullanarak Birleştirin
url: /tr/php-java/merger/pptm/
keywords: Birleştirme PPTM, Birleştirme PPTM, Birleştirme PPTM, PowerPoint, Sunum, PHP, Aspose
description: PHP'de birden çok PPTM dosyasını birleştirin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP'de PPTM dosyalarını birleştirme" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası PHP API." >}}

{{% blocks/products/pf/feature-page-section h2="PHP'de PPTM ile birleştirme" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, birden çok PPTM sunumunu birleştirmenin esnek yollarını sunar. Bir sunumu diğerine birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunumda etkili bir şekilde birleştirmiş olursunuz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenizi sağlar. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan sunumları tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PPTM dosyalarını PHP kullanarak birleştirme" %}}
PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{% blocks/products/pf/agp/code-block title="Birden çok PPTM dosyasını tek dosyada birleştirmek için PHP kodu" offSpacer="true" %}}


```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres1 = new Presentation("document1.pptm");
$pres2 = new Presentation("document2.pptm");
try
{
    for ($i = 0; $i < java_values($pres2->getSlides()->size()); $i++) 
    {
        $pres1->getSlides()->addClone($pres2->getSlides()->get_Item($i));
    }

    $pres1->save("merged.pptm", SaveFormat::Pptm);
}
finally
{
    if ($pres1 != null) $pres1->dispose();
    if ($pres2 != null) $pres2->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API kullanarak PPTM nasıl birleştirilir" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="PHP'de iki PPTM dosyasını birleştirme ve sonucu PPTM olarak kaydetme adımları bunlardır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for PHP'yi Java aracılığıyla** kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Birleştirmek istediğiniz PPTM dosyalarını yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan PPTM belgesini kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPTM öğesini Desteklenen Diğer Biçimlere Dışa Aktarın" subTitle="Ayrıca PPTM öğesini birleştirebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/fodp/" name="FODP" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}