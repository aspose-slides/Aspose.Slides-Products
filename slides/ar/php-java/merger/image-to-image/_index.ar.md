---
title: دمج الصور في PHP
url: /ar/php-java/merger/image-to-image/
keywords: دمج الصورة ، الصورة إلى الصورة ، الانضمام إلى الصور ، الجمع بين الصور ، PHP API ، مكتبة PHP
description: دمج الصورة بالصورة في PHP. استخدم مكتبة PHP API لدمج الصور
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="دمج الصورة في PHP" h2="مكتبة PHP عالية السرعة ومتعددة المنصات لدمج الصور باستخدام كود PHP" >}}

{{% blocks/products/pf/feature-page-section h2="دمج الصورة بالصورة باستخدام Aspose.Slides" %}}

[** Aspose.Slides for PHP عبر Java **](https://products.aspose.com/slides/ar/php-java/) هي مكتبة PHP قوية تُستخدم لدمج ومعالجة العروض التقديمية والصور والملفات الأخرى. عندما تدمج صورة مع صورة ، فأنت تدمج بشكل فعال صورتين للحصول على صورة واحدة.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="دمج الصورة بالصورة في PHP" %}}
باستخدام [** Aspose.Slides for PHP عبر Java **](https://products.aspose.com/slides/ar/php-java/) ، يمكنك دمج ملفات الصور بسرعة ببضعة سطور من التعليمات البرمجية

{{% blocks/products/pf/agp/code-block title="كود PHP لدمج الصورة بالصورة" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename1 = 'image1.png';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }

    $filename2 = 'image1.png';
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
    $javafile = new Java("java.io.File", "merged-image.png");
    $imageio->write($img, "PNG", $javafile);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية دمج الصور في PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
تثبيت ** Aspose.Slides for PHP عبر Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف المكتبة كمرجع في مشروعك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل الصور التي تريد دمجها كإطارات صور.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ الصورة الناتجة.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="دمج ملفات PDF على الإنترنت" sectionDescription="[كيفية دمج ملفات PDF في بايثون](https://products.aspose.com/slides/ar/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="دمج الملفات الأخرى" subTitle="يمكنك أيضًا دمج الملفات بتنسيقات أخرى للحصول على ملف واحد" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}