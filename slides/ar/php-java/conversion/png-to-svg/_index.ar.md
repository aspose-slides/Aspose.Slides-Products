---
title: تحويل PNG إلى SVG في PHP
url: /ar/php-java/conversion/png-to-svg/
keywords: PNG إلى SVG ، تحويل PNG إلى SVG ، PHP API ، PHP Library ، PNG ، SVG
description: تحويل PNG إلى SVG في PHP. استخدم PowerPoint PHP API لتحويل ملفات PNG إلى SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PNG إلى SVG في PHP" h2="مكتبة PowerPoint PHP قوية تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PNG إلى SVG في PHP" %}}

[** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) هي مكتبة PHP قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل PNG إلى SVG. باستخدام ** Aspose.Slides لـ PHP عبر Java ** ، يمكن لأي مطور أو تطبيق تحويل ملفات PNG إلى SVG ببضعة أسطر من كود PHP.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، يقوم Aspose.Slides for PHP بتصدير ملفات PNG إلى SVG تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل PNG إلى SVG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل PNG إلى SVG باستخدام PHP" %}}
لتحويل PNG إلى SVG ، ستحتاج إلى إنشاء عرض تقديمي من ملف PNG وحفظه بتنسيق SVG.

{{% blocks/products/pf/agp/code-block title="كود PHP لتحويل PNG إلى SVG" offSpacer="true" %}}

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
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".svg");
        $slide->writeAsSvg($javafos);
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

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PNG إلى SVG باستخدام Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل PNG إلى SVG في PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [** Aspose.Slides for PHP عبر Java **](https://products.aspose.com/slides/ar/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع PHP الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح المصدر PNG ملفات في PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل PNG إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PNG وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}