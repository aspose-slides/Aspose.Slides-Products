---
title: تبدیل JPG به PNG در PHP
url: /fa/php-java/conversion/jpg-to-png/
keywords: JPG به PNG، تبدیل JPG به PNG، PHP API، PHP Library، JPG، PNG
description: تبدیل JPG به PNG در PHP. از PowerPoint PHP API برای تبدیل فایل‌های JPG به PNG استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل JPG به PNG در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP که به توسعه برنامه هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می کند." >}}

{{% blocks/products/pf/feature-page-section h2="تبدیل JPG به PNG در PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل JPG به PNG ارائه می‌کند. با استفاده از **Aspose.Slides برای PHP از طریق جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های JPG را تنها با چند خط کد PHP به PNG تبدیل کند.

Aspose.Slides برای PHP به عنوان یک API مدرن برای پردازش اسناد، فایل‌های JPG را به فرمت‌های فایل PNG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد JPG را به PNG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از PHP، JPG را به PNG تبدیل کنید" %}}
برای تبدیل JPG به PNG، باید Presentation را از فایل JPG ایجاد کنید و آن را به عنوان PNG ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد PHP برای تبدیل JPG به PNG" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
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
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
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

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل JPG به PNG با استفاده از Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل JPG به PNG در PHP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides برای PHP از طریق جاوا**](https://products.aspose.com/slides/fa/php-java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه PHP خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع JPG را در PHP باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PNG ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل JPG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید JPG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}