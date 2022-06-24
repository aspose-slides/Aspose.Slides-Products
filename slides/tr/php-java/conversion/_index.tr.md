---
title: PHP'de Microsoft PowerPoint Sunumunu PDF'ye Dönüştürme
url: /tr/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PPT'yi PDF'ye Dönüştürmek için PHP API. Sunumları PHP'de JPG, PNG ve diğer formatlara dönüştürün.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PHP'de Microsoft<sup>®</sup> PowerPoint Sunumunu PDF'ye Dönüştürme" h2="PPT'yi PDF, PNG, HTML, JPEG, PPTX ve diğer formatlara dönüştürmek için farklı dönüştürme durumları için PHP Kaynak Kodları." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Java aracılığıyla Aspose.Slides for PHP](https://products.aspose.com/slides/tr/php-java/) sunumları işlemek ve bunlarla çalışmak için kullanılan güçlü bir şirket içi sınıf kitaplığıdır. Geliştiricilerin PowerPoint'i hızlı ve doğru bir şekilde PDF'ye dönüştürmesi kolaydır. İş süreçlerini otomatikleştirmek için sonuçları kısa sürede alın. Burada, herhangi bir girişi [desteklenen PowerPoint formatlarını](https://docs.aspose.com/slides/php-java/supported-file-formats/) okumak veya yüklemek ve desteklenen herhangi bir çıktı formatına yazmak veya kaydetmek için birkaç durumu tartışıyoruz. . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PHP'de PowerPoint'ten PDF'ye Dönüştürme" %}}
[Aspose.Slides](https://products.aspose.com/slides/tr/php-java/) PowerPoint PPT, PPTX ve OpenOffice ODP formatlarındaki dosyaları PDF'ye dönüştürmenize olanak tanır. Bir sunumu PDF'ye dönüştürmek için dosya adını ve kaydetme biçimini "Presentation.save" yöntemine aktarmanız yeterlidir. "Sunum" sınıfı, tüm PPT, PPTX veya ODP sunumunu bir PDF belgesine dönüştürmek için çağrılabilen "kaydet" yöntemini gösterir.

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint'ten PDF'ye Dönüştürme" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="PHP'de PDF'den PPT'ye Dönüştürme" %}}
[Aspose.Slides](https://products.aspose.com/slides/tr/php-java/), sunumları PDF'lerden içe aktarmanıza olanak tanır. Esasen, bir PDF'yi bir PowerPoint sunumuna dönüştürebilirsiniz. PDF'yi Powerpoint'e dönüştürmek için şu adımları izleyin:
- 'Sunum' sınıfının bir nesnesini örnekleyin.
- `addFromPdf` yöntemini çağırın ve PDF dosyasını iletin.
- Dosyayı PowerPoint formatında kaydetmek için "kaydet" yöntemini kullanın.

{{% blocks/products/pf/feature-page-code h3="PHP PDF'den Powerpoint'e Dönüştürme" %}}

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
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="PHP'de özel seçeneklerle PPT'yi PDF'ye dönüştürün" %}}

PowerPoint slaytlarını doğru bir şekilde PDF'ye dönüştürmek için, Programcılar belgeyi `Sunum` sınıfını kullanarak yükleyebilir ve metin sıkıştırma düzeyi, Jpeg kalitesi, meta dosyaların davranışı, gizli slaytları dönüştürme ve seçme gibi tüm özel ve özel seçenekler için `PdfOptions` sınıfını kullanabilir. özel slaytlar ve daha fazlası. Hatta dönüştürülen PDF dosyasını parola ile koruma seçeneği de vardır.
{{% blocks/products/pf/feature-page-code h3="Özel ayarlarla PHP PowerPoint'ten PDF'ye Dönüştürme" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="PHP'de Microsoft PowerPoint'ten HTML'ye Dönüştürme" %}}
Sunumları web sayfalarına gömmek gerektiğinde, slaytları HTML'ye dönüştürmek gerekir. 
{{% blocks/products/pf/feature-page-code h3="PowerPoint'ten HTML'ye Dönüştürme için PHP Kodu" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint'i JPG'ye Dönüştür" %}}
Microsoft<sup>®</sup> PowerPoint formatlarını JPEG, PNG, TIFF vb. resimlere dönüştürmek, çoğunlukla slayt küçük resimleri oluşturmak için kullanılan başka bir yaygın kullanım durumudur. 
{{% blocks/products/pf/feature-page-code h3="PHP PPT'den JPG'ye Dönüştürücü Kodu" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>  
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}