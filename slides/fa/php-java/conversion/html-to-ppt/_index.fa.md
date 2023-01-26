---
title: تبدیل HTML به PPT در PHP
url: /fa/php-java/conversion/html-to-ppt/
keywords: HTML به PPT، تبدیل HTML به PPT، PHP API، PHP Library، HTML، PPT
description: تبدیل HTML به PPT در PHP. از PowerPoint PHP API برای تبدیل فایل‌های HTML به PPT استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل HTML به PPT در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP که به توسعه برنامه هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می کند." >}}

{{% blocks/products/pf/feature-page-section h2="تبدیل HTML به PPT در PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل HTML به PPT ارائه می‌کند. با استفاده از **Aspose.Slides برای PHP از طریق جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های HTML را تنها با چند خط کد PHP به PPT تبدیل کند.

Aspose.Slides برای PHP به عنوان یک API مدرن برای پردازش اسناد، فایل‌های HTML را به فرمت‌های فایل PPT صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد HTML را به PPT و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از PHP، HTML را به PPT تبدیل کنید" %}}
برای تبدیل HTML به PPT، باید Presentation را از فایل HTML ایجاد کنید و آن را به عنوان PPT ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد PHP برای تبدیل HTML به PPT" offSpacer="true" %}}

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
    $pres->save("output.ppt", SaveFormat::Ppt);        
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل HTML به PPT با استفاده از Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل HTML به PPT در PHP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides برای PHP از طریق جاوا**](https://products.aspose.com/slides/fa/php-java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه PHP خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع HTML را در PHP باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PPT ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل HTML به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید HTML را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}