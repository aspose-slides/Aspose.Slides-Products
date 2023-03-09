---
title: ادغام تصاویر JPG در PHP
url: /fa/php-java/merger/jpg-to-jpg/
keywords: ادغام JPG، JPEG به JPG، پیوستن به JPG، ترکیب JPG، PHP API، کتابخانه PHP
description: ادغام JPG به JPG در PHP. از API کتابخانه PHP برای ترکیب فایل های JPG استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="ادغام JPG در PHP" h2="کتابخانه PHP پرسرعت و کراس پلتفرم برای ادغام تصاویر JPG با استفاده از کد PHP" >}}

{{% blocks/products/pf/feature-page-section h2="ادغام JPG به JPG با استفاده از Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP است که برای ادغام و دستکاری ارائه ها، تصاویر و فایل های دیگر استفاده می شود. هنگامی که JPG را با JPG ادغام می کنید، به طور موثر دو تصویر را برای دریافت یک تصویر ترکیب می کنید.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="ادغام JPG به JPG در PHP" %}}
با استفاده از [**Aspose.Slides برای PHP از طریق جاوا**](https://products.aspose.com/slides/fa/php-java/)، می توانید فایل های JPG را به سرعت تنها با چند خط کد ادغام کنید.

{{% blocks/products/pf/agp/code-block title="کد PHP برای ادغام JPG به JPG" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام JPG در PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای PHP از طریق جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/php-java/installation/) را ببینید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از کلاس Presentation ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های JPG را که می خواهید به عنوان قاب عکس ادغام کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تصویر JPG حاصل را ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="فایل های دیگر را ادغام کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ترکیب کنید تا یک فایل واحد بدست آورید" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}