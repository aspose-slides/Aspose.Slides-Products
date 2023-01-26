---
title: PHP'de PDF öğesini PNG biçimine dönüştürün
url: /tr/php-java/conversion/pdf-to-png/
keywords: PDF'tan PNG'a, PDF'tan PNG'a Dönüştürme, PHP API, PHP Kitaplığı, PDF, PNG
description: PHP'de PDF öğesini PNG biçimine dönüştürün. PDF dosyalarını PNG biçimine dönüştürmek için PowerPoint PHP API kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP'de PDF öğesini PNG biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisiyle uygulama geliştirmeye yardımcı olan güçlü PowerPoint PHP kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="PHP'de PDF öğesini PNG biçimine dönüştürün" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, PDF biçimini PNG biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for PHP via Java** kullanarak, herhangi bir geliştirici veya uygulama yalnızca birkaç satırlık PHP koduyla PDF dosyalarını PNG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for PHP, PDF dosyalarını hızlı bir şekilde PNG dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, PDF biçimini PNG biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP kullanarak PDF biçimini PNG biçimine dönüştürün" %}}
PDF dosyasını PNG biçimine dönüştürmek için, PDF dosyasından Sunu oluşturmanız ve onu PNG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PDF biçimini PNG biçimine dönüştürmek için PHP kodu" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API kullanarak PDF biçimini PNG biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PHP'de PDF biçimini PNG biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PDF dosyalarını PHP'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PNG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca PDF dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}