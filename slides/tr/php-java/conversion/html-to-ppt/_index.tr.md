---
title: PHP'de HTML öğesini PPT biçimine dönüştürün
url: /tr/php-java/conversion/html-to-ppt/
keywords: HTML'tan PPT'a, HTML'tan PPT'a Dönüştürme, PHP API, PHP Kitaplığı, HTML, PPT
description: PHP'de HTML öğesini PPT biçimine dönüştürün. HTML dosyalarını PPT biçimine dönüştürmek için PowerPoint PHP API kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP'de HTML öğesini PPT biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisiyle uygulama geliştirmeye yardımcı olan güçlü PowerPoint PHP kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="PHP'de HTML öğesini PPT biçimine dönüştürün" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, HTML biçimini PPT biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for PHP via Java** kullanarak, herhangi bir geliştirici veya uygulama yalnızca birkaç satırlık PHP koduyla HTML dosyalarını PPT dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for PHP, HTML dosyalarını hızlı bir şekilde PPT dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, HTML biçimini PPT biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP kullanarak HTML biçimini PPT biçimine dönüştürün" %}}
HTML dosyasını PPT biçimine dönüştürmek için, HTML dosyasından Sunu oluşturmanız ve onu PPT olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="HTML biçimini PPT biçimine dönüştürmek için PHP kodu" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
        
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename = 'file.html';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $pres->getSlides()->addFromHtml($contents);        
    $pres->save("output.ppt", SaveFormat::Ppt);        
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API kullanarak HTML biçimini PPT biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PHP'de HTML biçimini PPT biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak HTML dosyalarını PHP'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPT dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="HTML biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca HTML dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}