---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP'de PPS öğesini PPT biçimine dönüştürün
weight: 1620
url: /tr/php-java/conversion/pps-to-ppt/ 
keywords: "Convert, PowerPoint, PPS, PPT, Presentation, PHP"
description: PPS - PPT PHP dönüşümü için örnek kod. PPS dosyalarını PPT dosyalarına toplu olarak dönüştürmek için PowerPoint PHP API'sini kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP'de PPS öğesini PPT biçimine dönüştürün" h2="PPS öğesini PPT biçimine dönüştürmek için güçlü PowerPoint PHP kitaplığı"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de PPS öğesini PPT biçimine dönüştürün" %}}

PPS dosyalarını programlı olarak PPT biçimine dönüştürmeniz mi gerekiyor? [*Aspose.Slides for PHP with Java*](https://products.aspose.com/slides/tr/php-java/) kullanarak herhangi bir geliştirici, yalnızca birkaç satır PHP koduyla PPS biçimini PPT biçimine dönüştürebilir. .

Modern bir sunum işleme API'si olarak Aspose.Slides for PHP, PPS öğesinden hızlı bir şekilde PPT oluşturur. PPS - PPT dönüşümünün kalitesini doğrudan [tarayıcınızda](https://products.aspose.app/slides/conversion) test edin. Aspose PowerPoint PPTX kitaplığı, PPS dosyalarını birçok popüler formata dönüştürmenize olanak tanır.

Aşağıdaki komutu kullanarak kitaplığı [Composer](https://packagist.org/packages/aspose/slides) adresinden yükleyebilirsiniz:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de PPS öğesini PPT olarak kaydedin" %}}

PPS - PPT dönüşüm sürecinin bir gösterimini görmek için ücretsiz uygulamayı kullanın.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bu örnek kod, PPS - PPT PHP Dönüşümünü gösterir" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pps");
try
{
    $pres->save("output.ppt", SaveFormat::Ppt);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP'de PPS, PPT biçimine nasıl dönüştürülür" intro="PHP kullanarak bir PPS dosyasını PPT biçimine dönüştürme adımları bunlardır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPS dosyasını bir Presentation sınıfı örneğiyle yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu & SaveFormat.PPT parametresini belirtirken "save" yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPS dosyası belirtilen yola kaydedilecek{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="sistem gereksinimleri" intro="PHP dönüştürme örnek kaynak kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7'yi kurun, PHP'nin yolunu sistem "PATH" değişkenine ekleyin ve "php.ini" dosyasında "allow_url_include" öğesini "On" olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE'yi kurun 8. 'JAVA_HOME' ortam değişkenini kurulu JRE konumuna giden bir yol olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0'ı yükleyin (bkz. [daha fazla](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPS to PPT"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="PPS dosyasını başka birçok dosya biçimine de dönüştürebilirsiniz. Aşağıda desteklenen diğer dönüşümleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Bitmap Görüntüsü" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-fodp/" name="PPS TO FODP" description="OpenDocument Düz XML Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-gif/" name="PPS TO GIF" description="Grafik Değişim Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-html/" name="PPS TO HTML" description="Hiper Metin İşaretleme Dili" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-jpg/" name="PPS TO JPG" description="JPEG Resmi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument Sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument Standart Biçimi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-pdf/" name="PPS TO PDF" description="Taşınabilir Döküman Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-png/" name="PPS TO PNG" description="taşınabilir Ağ Grafikleri" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-potm/" name="PPS TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-potx/" name="PPS TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Makro Etkin Sunum Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Açık XML sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-svg/" name="PPS TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Etiketli Görüntü Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pps-to-xps/" name="PPS TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
