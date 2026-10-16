---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP'de PDF öğesini PPT biçimine dönüştürün
weight: 780
url: /tr/php-java/conversion/pdf-to-ppt/ 
keywords: "Convert, PowerPoint, PDF, PPT, Presentation, PHP"
description: PDF - PPT PHP dönüşümü için örnek kod. PDF dosyalarını PPT dosyalarına toplu olarak dönüştürmek için PowerPoint PHP API'sini kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP'de PDF öğesini PPT biçimine dönüştürün" h2="PDF öğesini PPT biçimine dönüştürmek için güçlü PowerPoint PHP kitaplığı"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de PDF öğesini PPT biçimine dönüştürün" %}}

PDF dosyalarını programlı olarak PPT biçimine dönüştürmeniz mi gerekiyor? [*Aspose.Slides for PHP with Java*](https://products.aspose.com/slides/tr/php-java/) kullanarak herhangi bir geliştirici, yalnızca birkaç satır PHP koduyla PDF biçimini PPT biçimine dönüştürebilir. .

Modern bir sunum işleme API'si olarak Aspose.Slides for PHP, PDF öğesinden hızlı bir şekilde PPT oluşturur. PDF - PPT dönüşümünün kalitesini doğrudan [tarayıcınızda](https://products.aspose.app/slides/conversion) test edin. Aspose PowerPoint PPTX kitaplığı, PDF dosyalarını birçok popüler formata dönüştürmenize olanak tanır.

Aşağıdaki komutu kullanarak kitaplığı [Composer](https://packagist.org/packages/aspose/slides) adresinden yükleyebilirsiniz:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de PDF öğesini PPT olarak kaydedin" %}}

PDF - PPT dönüşüm sürecinin bir gösterimini görmek için ücretsiz uygulamayı kullanın.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bu örnek kod, PDF - PPT PHP Dönüşümünü gösterir" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP'de PDF, PPT biçimine nasıl dönüştürülür" intro="PHP kullanarak bir PDF dosyasını PPT biçimine dönüştürme adımları bunlardır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF dosyasını bir Presentation sınıfı örneğiyle yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu & SaveFormat.PPT parametresini belirtirken "save" yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF dosyası belirtilen yola kaydedilecek{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="sistem gereksinimleri" intro="PHP dönüştürme örnek kaynak kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7'yi kurun, PHP'nin yolunu sistem "PATH" değişkenine ekleyin ve "php.ini" dosyasında "allow_url_include" öğesini "On" olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE'yi kurun 8. 'JAVA_HOME' ortam değişkenini kurulu JRE konumuna giden bir yol olarak ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0'ı yükleyin (bkz. [daha fazla](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PDF to PPT"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="PDF dosyasını başka birçok dosya biçimine de dönüştürebilirsiniz. Aşağıda desteklenen diğer dönüşümleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Bitmap Görüntüsü" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-fodp/" name="PDF TO FODP" description="OpenDocument Düz XML Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="Grafik Değişim Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-html/" name="PDF TO HTML" description="Hiper Metin İşaretleme Dili" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="JPEG Resmi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="OpenDocument Sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="OpenDocument Standart Biçimi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="taşınabilir Ağ Grafikleri" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-potm/" name="PDF TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pps/" name="PDF TO PPS" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Makro Etkin Sunum Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Açık XML sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="SWF Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Etiketli Görüntü Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
