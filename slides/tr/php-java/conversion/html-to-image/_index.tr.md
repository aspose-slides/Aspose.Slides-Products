---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP'de HTML öğesini Image biçimine dönüştürün
url: /tr/php-java/conversion/html-to-image/
keywords: HTML'tan Image'a, HTML'tan Image'a Dönüştürme, PHP API, PHP Kitaplığı, HTML, Image
description: PHP'de HTML öğesini Image biçimine dönüştürün. HTML dosyalarını Image biçimine dönüştürmek için PowerPoint PHP API kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP'de HTML öğesini Image biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisiyle uygulama geliştirmeye yardımcı olan güçlü PowerPoint PHP kitaplığı." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP kullanarak HTML biçimini Image biçimine dönüştürün" variant="code" %}}

HTML dosyasını Image biçimine dönüştürmek için, HTML dosyasından Sunu oluşturmanız ve onu Image olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML biçimini Image biçimine dönüştürmek için PHP kodu" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de HTML öğesini Image biçimine dönüştürün" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, HTML biçimini Image biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for PHP via Java** kullanarak, herhangi bir geliştirici veya uygulama yalnızca birkaç satırlık PHP koduyla HTML dosyalarını Image dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for PHP, HTML dosyalarını hızlı bir şekilde Image dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, HTML biçimini Image biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for PHP API kullanarak HTML biçimini Image biçimine dönüştürme" intro="Bunlar, PHP'de HTML biçimini Image biçimine dönüştürme adımlarıdır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak HTML dosyalarını PHP'de açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu Image dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ücretsiz Çevrimiçi Dönüştürücü"
  description="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="HTML biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca HTML dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
