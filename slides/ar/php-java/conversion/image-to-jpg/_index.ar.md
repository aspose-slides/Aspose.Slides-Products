---
title: تحويل Image إلى JPG في PHP
url: /ar/php-java/conversion/image-to-jpg/
keywords: Image إلى JPG ، تحويل Image إلى JPG ، PHP API ، PHP Library ، Image ، JPG
description: تحويل Image إلى JPG في PHP. استخدم PowerPoint PHP API لتحويل ملفات Image إلى JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل Image إلى JPG في PHP" h2="مكتبة PowerPoint PHP قوية تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل Image إلى JPG في PHP" %}}

[** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) هي مكتبة PHP قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل Image إلى JPG. باستخدام ** Aspose.Slides لـ PHP عبر Java ** ، يمكن لأي مطور أو تطبيق تحويل ملفات Image إلى JPG ببضعة أسطر من كود PHP.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، يقوم Aspose.Slides for PHP بتصدير ملفات Image إلى JPG تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل Image إلى JPG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل Image إلى JPG باستخدام PHP" %}}
لتحويل Image إلى JPG ، ستحتاج إلى إنشاء عرض تقديمي من ملف Image وحفظه بتنسيق JPG.

{{% blocks/products/pf/agp/code-block title="كود PHP لتحويل Image إلى JPG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل Image إلى JPG باستخدام Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل Image إلى JPG في PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [** Aspose.Slides for PHP عبر Java **](https://products.aspose.com/slides/ar/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع PHP الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح المصدر Image ملفات في PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل Image إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل Image وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}