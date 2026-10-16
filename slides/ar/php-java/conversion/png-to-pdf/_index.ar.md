---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PNG إلى PDF في PHP
url: /ar/php-java/conversion/png-to-pdf/
keywords: PNG إلى PDF ، تحويل PNG إلى PDF ، PHP API ، PHP Library ، PNG ، PDF
description: تحويل PNG إلى PDF في PHP. استخدم PowerPoint PHP API لتحويل ملفات PNG إلى PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PNG إلى PDF في PHP" h2="مكتبة PowerPoint PHP قوية تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PNG إلى PDF باستخدام PHP" variant="code" %}}

لتحويل PNG إلى PDF ، ستحتاج إلى إنشاء عرض تقديمي من ملف PNG وحفظه بتنسيق PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود PHP لتحويل PNG إلى PDF" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PNG إلى PDF في PHP" %}}

[** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) هي مكتبة PHP قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل PNG إلى PDF. باستخدام ** Aspose.Slides لـ PHP عبر Java ** ، يمكن لأي مطور أو تطبيق تحويل ملفات PNG إلى PDF ببضعة أسطر من كود PHP.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، يقوم Aspose.Slides for PHP بتصدير ملفات PNG إلى PDF تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل PNG إلى PDF والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PNG إلى PDF باستخدام Aspose.Slides for PHP API" intro="هذه هي خطوات تحويل PNG إلى PDF في PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت [** Aspose.Slides for PHP عبر Java **](https://products.aspose.com/slides/ar/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع PHP الخاص بك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح المصدر PNG ملفات في PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حفظ النتيجة كملف PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="محول مجاني على الإنترنت"
  description="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويل PNG إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PNG وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
