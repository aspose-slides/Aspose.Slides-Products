---
title: PHP'de PDF öğesini POTM biçimine dönüştürün
weight: 730
url: /tr/php-java/conversion/pdf-to-potm/ 
keywords: "Convert, PowerPoint, PDF, POTM, Presentation, PHP"
description: PDF - POTM PHP dönüşümü için örnek kod. PDF dosyalarını POTM dosyalarına toplu olarak dönüştürmek için PowerPoint PHP API'sini kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PHP'de PDF öğesini POTM biçimine dönüştürün" h2="PDF öğesini POTM biçimine dönüştürmek için güçlü PowerPoint PHP kitaplığı" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PHP'de PDF öğesini POTM biçimine dönüştürün" %}}

PDF dosyalarını programlı olarak POTM biçimine dönüştürmeniz mi gerekiyor? [*Aspose.Slides for PHP with Java*](https://products.aspose.com/slides/tr/php-java/) kullanarak herhangi bir geliştirici, yalnızca birkaç satır PHP koduyla PDF biçimini POTM biçimine dönüştürebilir. .

Modern bir sunum işleme API'si olarak Aspose.Slides for PHP, PDF öğesinden hızlı bir şekilde POTM oluşturur. PDF - POTM dönüşümünün kalitesini doğrudan [tarayıcınızda](https://products.aspose.app/slides/conversion) test edin. Aspose PowerPoint PPTX kitaplığı, PDF dosyalarını birçok popüler formata dönüştürmenize olanak tanır.

Aşağıdaki komutu kullanarak kitaplığı [Composer](https://packagist.org/packages/aspose/slides) adresinden yükleyebilirsiniz:

{{% blocks/products/pf/agp/code-block title="Konsol/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="PHP'de PDF, POTM biçimine nasıl dönüştürülür" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="PHP kullanarak bir PDF dosyasını POTM biçimine dönüştürme adımları bunlardır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PDF dosyasını bir Presentation sınıfı örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Çıktı dosyası yolunu & SaveFormat.POTM parametresini belirtirken "save" yöntemini çağırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PDF dosyası belirtilen yola kaydedilecek
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 PHP dönüştürme örnek kaynak kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

1. PHP 7'yi kurun, PHP'nin yolunu sistem "PATH" değişkenine ekleyin ve "php.ini" dosyasında "allow_url_include" öğesini "On" olarak ayarlayın.
1. JRE'yi kurun 8. 'JAVA_HOME' ortam değişkenini kurulu JRE konumuna giden bir yol olarak ayarlayın.
1. Apache Tomcat 8.0'ı yükleyin (bkz. [daha fazla](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, PDF - POTM PHP Dönüşümünü gösterir" offSpacer="" %}}

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
    $pres->save("output.potm", SaveFormat::Potm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="PHP'de PDF öğesini POTM olarak kaydedin" %}}
PDF - POTM dönüşüm sürecinin bir gösterimini görmek için ücretsiz uygulamayı kullanın. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PDF to POTM" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="PDF dosyasını başka birçok dosya biçimine de dönüştürebilirsiniz. Aşağıda desteklenen diğer dönüşümleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Bitmap Görüntüsü" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-fodp/" name="PDF TO FODP" description="OpenDocument Düz XML Sunumu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="Grafik Değişim Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-html/" name="PDF TO HTML" description="Hiper Metin İşaretleme Dili" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="JPEG Resmi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="OpenDocument Sunum Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="OpenDocument Standart Biçimi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="taşınabilir Ağ Grafikleri" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pps/" name="PDF TO PPS" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Makro Etkin Sunum Dosyası" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Açık XML sunum Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="SWF Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Etiketli Görüntü Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="XML Kağıt Özellikleri" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}