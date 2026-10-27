---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP'de POT öğesini SVG biçimine dönüştürün
weight: 1020
url: /tr/php-java/conversion/pot-to-svg/ 
keywords: "Convert, PowerPoint, POT, SVG, Presentation, PHP"
description: POT - SVG PHP dönüşümü için örnek kod. POT dosyalarını SVG dosyalarına toplu olarak dönüştürmek için PowerPoint PHP API'sini kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP'de POT öğesini SVG biçimine dönüştürün" h2="POT öğesini SVG biçimine dönüştürmek için güçlü PowerPoint PHP kitaplığı"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de POT öğesini SVG biçimine dönüştürün" %}}

POT dosyalarını programlı olarak SVG biçimine dönüştürmeniz mi gerekiyor? [*Aspose.Slides for PHP with Java*](https://products.aspose.com/slides/tr/php-java/) kullanarak herhangi bir geliştirici, yalnızca birkaç satır PHP koduyla POT biçimini SVG biçimine dönüştürebilir. .

Modern bir sunum işleme API'si olarak Aspose.Slides for PHP, POT öğesinden hızlı bir şekilde SVG oluşturur. POT - SVG dönüşümünün kalitesini doğrudan [tarayıcınızda](https://products.aspose.app/slides/conversion) test edin. Aspose PowerPoint PPTX kitaplığı, POT dosyalarını birçok popüler formata dönüştürmenize olanak tanır.

Aşağıdaki komutu kullanarak kitaplığı [Composer](https://packagist.org/packages/aspose/slides) adresinden yükleyebilirsiniz:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de POT öğesini SVG olarak kaydedin" %}}

POT - SVG dönüşüm sürecinin bir gösterimini görmek için ücretsiz uygulamayı kullanın.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bu örnek kod, POT - SVG PHP Dönüşümünü gösterir" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP'de POT, SVG biçimine nasıl dönüştürülür" intro="PHP kullanarak bir POT dosyasını SVG biçimine dönüştürme adımları bunlardır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POT dosyasını bir Presentation sınıfı örneğiyle yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu & SaveFormat.SVG parametresini belirtirken "save" yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POT dosyası belirtilen yola kaydedilecek{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="sistem gereksinimleri" intro="PHP dönüştürme örnek kaynak kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7'yi kurun, PHP'nin yolunu sistem "PATH" değişkenine ekleyin ve "php.ini" dosyasında "allow_url_include" öğesini "On" olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE'yi kurun 8. 'JAVA_HOME' ortam değişkenini kurulu JRE konumuna giden bir yol olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0'ı yükleyin (bkz. [daha fazla](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides ile geliştirildi" title="POT dosyasını çevrimiçi olarak SVG biçimine dönüştürün" description="Ücretsiz Aspose.Slides Conversion uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/tr/php-java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi POT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Conversion uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" upload="Dosyanızı bırakın veya yükleyin" saveAs="Farklı kaydet" convert="Dönüştür" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyaları nasıl dönüştürdüğünü görün.
- POT dosyalarını yükleyin ve SVG olarak kaydedin.
- Sonucu indirin veya daha fazla dosya dönüştürün.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="POT dosyasını başka birçok dosya biçimine de dönüştürebilirsiniz. Aşağıda desteklenen diğer dönüşümleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-bmp/" name="POT TO BMP" description="Bitmap Görüntüsü" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-fodp/" name="POT TO FODP" description="OpenDocument Düz XML Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-gif/" name="POT TO GIF" description="Grafik Değişim Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-html/" name="POT TO HTML" description="Hiper Metin İşaretleme Dili" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-jpg/" name="POT TO JPG" description="JPEG Resmi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocument Sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-otp/" name="POT TO OTP" description="OpenDocument Standart Biçimi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-pdf/" name="POT TO PDF" description="Taşınabilir Döküman Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-png/" name="POT TO PNG" description="taşınabilir Ağ Grafikleri" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-potm/" name="POT TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-potx/" name="POT TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-pps/" name="POT TO PPS" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-ppsx/" name="POT TO PPSX" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-pptm/" name="POT TO PPTM" description="Makro Etkin Sunum Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-pptx/" name="POT TO PPTX" description="Açık XML sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-swf/" name="POT TO SWF" description="SWF Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-tiff/" name="POT TO TIFF" description="Etiketli Görüntü Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pot-to-xps/" name="POT TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
