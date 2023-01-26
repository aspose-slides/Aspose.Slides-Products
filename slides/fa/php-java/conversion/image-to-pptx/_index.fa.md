---
title: تبدیل Image به PPTX در PHP
url: /fa/php-java/conversion/image-to-pptx/
keywords: Image به PPTX، تبدیل Image به PPTX، PHP API، PHP Library، Image، PPTX
description: تبدیل Image به PPTX در PHP. از PowerPoint PHP API برای تبدیل فایل‌های Image به PPTX استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل Image به PPTX در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP که به توسعه برنامه هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می کند." >}}

{{% blocks/products/pf/feature-page-section h2="تبدیل Image به PPTX در PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل Image به PPTX ارائه می‌کند. با استفاده از **Aspose.Slides برای PHP از طریق جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های Image را تنها با چند خط کد PHP به PPTX تبدیل کند.

Aspose.Slides برای PHP به عنوان یک API مدرن برای پردازش اسناد، فایل‌های Image را به فرمت‌های فایل PPTX صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد Image را به PPTX و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از PHP، Image را به PPTX تبدیل کنید" %}}
برای تبدیل Image به PPTX، باید Presentation را از فایل Image ایجاد کنید و آن را به عنوان PPTX ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد PHP برای تبدیل Image به PPTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل Image به PPTX با استفاده از Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل Image به PPTX در PHP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides برای PHP از طریق جاوا**](https://products.aspose.com/slides/fa/php-java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه PHP خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع Image را در PHP باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PPTX ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل Image به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید Image را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}