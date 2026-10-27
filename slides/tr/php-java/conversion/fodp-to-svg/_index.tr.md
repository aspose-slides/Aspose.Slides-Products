---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP'de FODP öğesini SVG biçimine dönüştürün
weight: 180
url: /tr/php-java/conversion/fodp-to-svg/ 
keywords: "Convert, PowerPoint, FODP, SVG, Presentation, PHP"
description: FODP - SVG PHP dönüşümü için örnek kod. FODP dosyalarını SVG dosyalarına toplu olarak dönüştürmek için PowerPoint PHP API'sini kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP'de FODP öğesini SVG biçimine dönüştürün" h2="FODP öğesini SVG biçimine dönüştürmek için güçlü PowerPoint PHP kitaplığı"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de FODP öğesini SVG biçimine dönüştürün" %}}

FODP dosyalarını programlı olarak SVG biçimine dönüştürmeniz mi gerekiyor? [*Aspose.Slides for PHP with Java*](https://products.aspose.com/slides/tr/php-java/) kullanarak herhangi bir geliştirici, yalnızca birkaç satır PHP koduyla FODP biçimini SVG biçimine dönüştürebilir. .

Modern bir sunum işleme API'si olarak Aspose.Slides for PHP, FODP öğesinden hızlı bir şekilde SVG oluşturur. FODP - SVG dönüşümünün kalitesini doğrudan [tarayıcınızda](https://products.aspose.app/slides/conversion) test edin. Aspose PowerPoint PPTX kitaplığı, FODP dosyalarını birçok popüler formata dönüştürmenize olanak tanır.

Aşağıdaki komutu kullanarak kitaplığı [Composer](https://packagist.org/packages/aspose/slides) adresinden yükleyebilirsiniz:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de FODP öğesini SVG olarak kaydedin" %}}

FODP - SVG dönüşüm sürecinin bir gösterimini görmek için ücretsiz uygulamayı kullanın.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bu örnek kod, FODP - SVG PHP Dönüşümünü gösterir" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".svg");
        $slide->writeAsSvg($javafos);
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

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP'de FODP, SVG biçimine nasıl dönüştürülür" intro="PHP kullanarak bir FODP dosyasını SVG biçimine dönüştürme adımları bunlardır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FODP dosyasını bir Presentation sınıfı örneğiyle yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu & SaveFormat.SVG parametresini belirtirken "save" yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FODP dosyası belirtilen yola kaydedilecek{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="sistem gereksinimleri" intro="PHP dönüştürme örnek kaynak kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7'yi kurun, PHP'nin yolunu sistem "PATH" değişkenine ekleyin ve "php.ini" dosyasında "allow_url_include" öğesini "On" olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE'yi kurun 8. 'JAVA_HOME' ortam değişkenini kurulu JRE konumuna giden bir yol olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0'ı yükleyin (bkz. [daha fazla](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides ile geliştirildi" title="FODP dosyasını çevrimiçi olarak SVG biçimine dönüştürün" description="Ücretsiz Aspose.Slides Conversion uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/tr/php-java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi FODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Conversion uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" upload="Dosyanızı bırakın veya yükleyin" saveAs="Farklı kaydet" convert="Dönüştür" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyaları nasıl dönüştürdüğünü görün.
- FODP dosyalarını yükleyin ve SVG olarak kaydedin.
- Sonucu indirin veya daha fazla dosya dönüştürün.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="FODP dosyasını başka birçok dosya biçimine de dönüştürebilirsiniz. Aşağıda desteklenen diğer dönüşümleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bitmap Görüntüsü" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafik Değişim Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Hiper Metin İşaretleme Dili" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG Resmi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument Sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument Standart Biçimi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Taşınabilir Döküman Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="taşınabilir Ağ Grafikleri" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Makro Etkin Sunum Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Açık XML sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Etiketli Görüntü Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
