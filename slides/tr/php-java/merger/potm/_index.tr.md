---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: POTM Dosyalarını PHP Kullanarak Birleştirin
url: /tr/php-java/merger/potm/
keywords: Birleştirme POTM, Birleştirme POTM, Birleştirme POTM, PowerPoint, Sunum, PHP, Aspose
description: PHP'de birden çok POTM dosyasını birleştirin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP'de POTM dosyalarını birleştirme" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası PHP API." related="PPT,PPTX,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPTM,FODP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POTM dosyalarını PHP kullanarak birleştirme" variant="code" %}}

PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Birden çok POTM dosyasını tek dosyada birleştirmek için PHP kodu" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres1 = new Presentation("document1.potm");
$pres2 = new Presentation("document2.potm");
try
{
    for ($i = 0; $i < java_values($pres2->getSlides()->size()); $i++) 
    {
        $pres1->getSlides()->addClone($pres2->getSlides()->get_Item($i));
    }

    $pres1->save("merged.potm", SaveFormat::Potm);
}
finally
{
    if ($pres1 != null) $pres1->dispose();
    if ($pres2 != null) $pres2->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP'de POTM ile birleştirme" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir PHP kitaplığıdır. Ayrıca, birden çok POTM sunumunu birleştirmenin esnek yollarını sunar. Bir sunumu diğerine birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunumda etkili bir şekilde birleştirmiş olursunuz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenizi sağlar. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan sunumları tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile birleştirebilirsiniz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for PHP API kullanarak POTM nasıl birleştirilir" intro="PHP'de iki POTM dosyasını birleştirme ve sonucu POTM olarak kaydetme adımları bunlardır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for PHP'yi Java aracılığıyla** kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize referans olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Birleştirmek istediğiniz POTM dosyalarını yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ortaya çıkan POTM belgesini kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides ile geliştirildi" title="POTM dosyalarını çevrimiçi birleştirin" description="Ücretsiz Aspose.Slides Merger uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/tr/php-java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi POTM dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Merger uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyaları nasıl birleştirdiğini görün.
- Birden fazla POTM dosyası yükleyin ve bunları tek bir dosyada birleştirin.
- Birleştirilmiş sonucu tek bir dosya olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="POTM öğesini Desteklenen Diğer Biçimlere Dışa Aktarın" subTitle="Ayrıca POTM öğesini birleştirebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/php-java/merger/fodp/" name="FODP" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
