---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ادغام تصاویر JPG در PHP
url: /fa/php-java/merger/jpg-to-jpg/
keywords: ادغام JPG، JPEG به JPG، پیوستن به JPG، ترکیب JPG، PHP API، کتابخانه PHP
description: ادغام JPG به JPG در PHP. از API کتابخانه PHP برای ترکیب فایل های JPG استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ادغام JPG در PHP" h2="کتابخانه PHP پرسرعت و کراس پلتفرم برای ادغام تصاویر JPG با استفاده از کد PHP" related="PNG,HTML,IMAGE,JPG,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ادغام JPG به JPG در PHP" variant="code" %}}

با استفاده از [**Aspose.Slides برای PHP از طریق جاوا**](https://products.aspose.com/slides/fa/php-java/)، می توانید فایل های JPG را به سرعت تنها با چند خط کد ادغام کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد PHP برای ادغام JPG به JPG" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename1 = 'image1.jpg';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }

    $filename2 = 'image1.jpg';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $image1 = $pres->getImages()->addImage($contents1);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 0, 0, 360, 540, $image1);
    
    $image2 = $pres->getImages()->addImage($contents2);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 360, 0, 360, 540, $image2);

    $img = $pres->getSlides()->get_Item(0)->getThumbnail(2, 2);
    $imageio = new Java("javax.imageio.ImageIO");
    $javafile = new Java("java.io.File", "merged-image.jpg");
    $imageio->write($img, "JPEG", $javafile);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ادغام JPG به JPG با استفاده از Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP است که برای ادغام و دستکاری ارائه ها، تصاویر و فایل های دیگر استفاده می شود. هنگامی که JPG را با JPG ادغام می کنید، به طور موثر دو تصویر را برای دریافت یک تصویر ترکیب می کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه ادغام JPG در PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides را برای PHP از طریق جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/php-java/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه از کلاس Presentation ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های JPG را که می خواهید به عنوان قاب عکس ادغام کنید بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تصویر JPG حاصل را ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="ساخته شده با Aspose.Slides" title="ادغام آنلاین فایل‌های JPG" description="برنامه رایگان Aspose.Slides Merger با [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/fa/php-java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های JPG شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Merger" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را ادغام می‌کند.
- چند فایل JPG را بارگذاری کنید و آن‌ها را در یک فایل ترکیب کنید.
- نتیجه ادغام‌شده را به‌صورت یک فایل دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="فایل های دیگر را ادغام کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ترکیب کنید تا یک فایل واحد بدست آورید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
