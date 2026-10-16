---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل PNG به PDF در PHP
url: /fa/php-java/conversion/png-to-pdf/
keywords: PNG به PDF، تبدیل PNG به PDF، PHP API، PHP Library، PNG، PDF
description: تبدیل PNG به PDF در PHP. از PowerPoint PHP API برای تبدیل فایل‌های PNG به PDF استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل PNG به PDF در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP که به توسعه برنامه هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می کند." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از PHP، PNG را به PDF تبدیل کنید" variant="code" %}}

برای تبدیل PNG به PDF، باید Presentation را از فایل PNG ایجاد کنید و آن را به عنوان PDF ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد PHP برای تبدیل PNG به PDF" >}}
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

    $pres->save("output.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل PNG به PDF در PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل PNG به PDF ارائه می‌کند. با استفاده از **Aspose.Slides برای PHP از طریق جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های PNG را تنها با چند خط کد PHP به PDF تبدیل کند.

Aspose.Slides برای PHP به عنوان یک API مدرن برای پردازش اسناد، فایل‌های PNG را به فرمت‌های فایل PDF صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد PNG را به PDF و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل PNG به PDF با استفاده از Aspose.Slides for PHP API" intro="این مراحل برای تبدیل PNG به PDF در PHP است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides برای PHP از طریق جاوا**](https://products.aspose.com/slides/fa/php-java/) را نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه PHP خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع PNG را در PHP باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل PDF ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="مبدل آنلاین رایگان"
  description="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل PNG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید PNG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
