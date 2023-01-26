---
title: PHP'de PNG öğesini PDF biçimine dönüştürün
url: /tr/php-java/conversion/png-to-pdf/
keywords: PNG'tan PDF'a, PNG'tan PDF'a Dönüştürme, PHP API, PHP Kitaplığı, PNG, PDF
description: PHP'de PNG öğesini PDF biçimine dönüştürün. PNG dosyalarını PDF biçimine dönüştürmek için PowerPoint PHP API kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP'de PNG öğesini PDF biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisiyle uygulama geliştirmeye yardımcı olan güçlü PowerPoint PHP kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="PHP'de PNG öğesini PDF biçimine dönüştürün" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, PNG biçimini PDF biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for PHP via Java** kullanarak, herhangi bir geliştirici veya uygulama yalnızca birkaç satırlık PHP koduyla PNG dosyalarını PDF dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for PHP, PNG dosyalarını hızlı bir şekilde PDF dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, PNG biçimini PDF biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP kullanarak PNG biçimini PDF biçimine dönüştürün" %}}
PNG dosyasını PDF biçimine dönüştürmek için, PNG dosyasından Sunu oluşturmanız ve onu PDF olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PNG biçimini PDF biçimine dönüştürmek için PHP kodu" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API kullanarak PNG biçimini PDF biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PHP'de PNG biçimini PDF biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PNG dosyalarını PHP'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PDF dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PNG biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca PNG dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}