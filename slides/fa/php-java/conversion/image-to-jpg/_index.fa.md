---
title: تبدیل Image به JPG در PHP
url: /fa/php-java/conversion/image-to-jpg/
keywords: Image به JPG، تبدیل Image به JPG، PHP API، PHP Library، Image، JPG
description: تبدیل Image به JPG در PHP. از PowerPoint PHP API برای تبدیل فایل‌های Image به JPG استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل Image به JPG در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP که به توسعه برنامه هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می کند." >}}

{{% blocks/products/pf/feature-page-section h2="تبدیل Image به JPG در PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل Image به JPG ارائه می‌کند. با استفاده از **Aspose.Slides برای PHP از طریق جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های Image را تنها با چند خط کد PHP به JPG تبدیل کند.

Aspose.Slides برای PHP به عنوان یک API مدرن برای پردازش اسناد، فایل‌های Image را به فرمت‌های فایل JPG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد Image را به JPG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از PHP، Image را به JPG تبدیل کنید" %}}
برای تبدیل Image به JPG، باید Presentation را از فایل Image ایجاد کنید و آن را به عنوان JPG ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد PHP برای تبدیل Image به JPG" offSpacer="true" %}}

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

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل Image به JPG با استفاده از Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل Image به JPG در PHP است." >}}

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
نتیجه را به عنوان فایل JPG ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل Image به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید Image را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}