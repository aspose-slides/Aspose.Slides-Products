---
title: PHP Kullanarak PDF, PPT, PPTX ve Diğer Birçok Dosya Formatını Birleştirin
url: /tr/php-java/merger/
keywords: Birleştirme, Birleştirme, PowerPoint, Sunum, PHP, Aspose
description: Birden çok dosyayı PHP PPT, PPTX, ODP, PDF, PNG, JPG ve çok daha fazlasında birleştirin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PHP'de Powerpoint, PDF, PPT veya diğer belgeleri bir araya getirin" h2="PPT, PPTX, PDF, PNG, JPEG ve diğer biçimleri birleştirmek için yüksek hızlı PHP kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="PHP kullanarak PPT, PPTX, PDF'yi birleştirin" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, çoklu PPT/PPTX sunumlarını birleştirmenin esnek yollarını sunar. Bir sunumu diğerine birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunumda etkili bir şekilde birleştirmiş olursunuz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenizi sağlar. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan sunumları tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP'de PowerPoint sunumlarını birleştirme" %}}
PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{% blocks/products/pf/agp/code-block title="PHP kullanarak PPTX dosyalarını birleştirme" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres1 = new Presentation("document1.ppt");
$pres2 = new Presentation("document2.ppt");
try
{
    for ($i = 0; $i < java_values($pres2->getSlides()->size()); $i++) 
    {
        $pres1->getSlides()->addClone($pres2->getSlides()->get_Item($i));
    }

    $pres1->save("merged.ppt", SaveFormat::Ppt);
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

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API kullanarak Sunumları birleştirme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, iki PPTX dosyasını birleştirme ve sonucu PHP'de PDF olarak kaydetme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://docs.aspose.com/slides/php-java/installation/) yükleyin. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PPTX dosyalarını PHP'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**addClone** yöntemini kullanarak PPTX dosyalarını birleştirin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunumu kaydedin ve sonucu tek bir PDF dosyası olarak alın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Birleştirilecek Diğer Desteklenen Biçimler" subTitle="Diğer dosya biçimlerini de birleştirebilirsiniz. Aşağıdaki desteklenen diğer biçimlere bakın." >}}

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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/pptm/" name="PPTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/fodp/" name="FODP" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/merger/pdf-to-pdf/" name="PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}