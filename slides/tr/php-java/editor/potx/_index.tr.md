---
title: POTX dosyasını PHP'de düzenleyin
url: /tr/php-java/editor/potx/
keywords: POTX Düzenle, PowerPoint'i Düzenle, POTX, PowerPoint, PHP API, PHP Kitaplığı
description: POTX dosyasını PHP'de düzenleyin. POTX dosyalarını düzenlemek için PHP kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="POTX dosyasını PHP'de düzenleyin" h2="PHP kodunu kullanarak POTX düzenlemek için yüksek hızlı ve platformlar arası PHP kitaplığı" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak POTX dosyasını düzenleyin" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/), sunumları hızlı ve kolay bir şekilde düzenlemek için güçlü bir PHP kitaplığıdır. Kullanıcılara, kısa sürede profesyonel görünümlü slaytlar oluşturmalarına yardımcı olacak çok çeşitli özellikler sunar. Aspose ile kullanıcılar sunumlarına metin düzenleyebilir, resimler, animasyonlar ve geçişler ekleyebilir, ayrıca yazı tipi ve renk seçimi gibi çeşitli biçimlendirme seçeneklerini uygulayabilir. Ek olarak, kitaplık hem PowerPoint (PPT) dosyaları hem de OpenOffice Presentation (ODP) formatları için destek sunarak sunumları herhangi bir uyumluluk sorunu ortaya çıkmadan farklı platformlarda paylaşmayı her zamankinden daha kolay hale getirir. Bir sonraki sunumunuzu oluştururken veya düzenlerken Aspose'un kütüphanesinin gücünden yararlanarak, slaytlarınızın her seferinde harika göründüğünden emin olacaksınız!
Bir POTX dosyasını, ona yeni bir metin satırı ekleyerek düzenleyebilirsiniz. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="POTX dosyasını PHP'de düzenleyin" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/tr/php-java/) kullanarak, POTX belgesine yalnızca bir metin satırıyla yeni bir metin satırı ekleyebilirsiniz. birkaç kod satırı.

{{% blocks/products/pf/agp/code-block title="POTX düzenlemesi için PHP kodu" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.potx", SaveFormat::Potx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PHP'de POTX nasıl düzenlenir" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for PHP'yi Java aracılığıyla** kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Düzenlemek istediğiniz POTX sunumunu yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Yeni bir metin satırı ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Değiştirilen dosyayı kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}