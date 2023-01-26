---
title: PHP'de JPG öğesini PNG biçimine dönüştürün
url: /tr/php-java/conversion/jpg-to-png/
keywords: JPG'tan PNG'a, JPG'tan PNG'a Dönüştürme, PHP API, PHP Kitaplığı, JPG, PNG
description: PHP'de JPG öğesini PNG biçimine dönüştürün. JPG dosyalarını PNG biçimine dönüştürmek için PowerPoint PHP API kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP'de JPG öğesini PNG biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisiyle uygulama geliştirmeye yardımcı olan güçlü PowerPoint PHP kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="PHP'de JPG öğesini PNG biçimine dönüştürün" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, JPG biçimini PNG biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for PHP via Java** kullanarak, herhangi bir geliştirici veya uygulama yalnızca birkaç satırlık PHP koduyla JPG dosyalarını PNG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for PHP, JPG dosyalarını hızlı bir şekilde PNG dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, JPG biçimini PNG biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP kullanarak JPG biçimini PNG biçimine dönüştürün" %}}
JPG dosyasını PNG biçimine dönüştürmek için, JPG dosyasından Sunu oluşturmanız ve onu PNG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="JPG biçimini PNG biçimine dönüştürmek için PHP kodu" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

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

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API kullanarak JPG biçimini PNG biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PHP'de JPG biçimini PNG biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak JPG dosyalarını PHP'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PNG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="JPG biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca JPG dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}