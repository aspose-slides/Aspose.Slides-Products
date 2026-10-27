---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: دمج ملفات HTML في PHP
url: /ar/php-java/merger/html-to-html/
keywords: دمج HTML ، HTML إلى HTML ، الانضمام إلى HTML ، الجمع بين HTML ، PHP API ، مكتبة PHP
description: دمج HTML مع HTML في PHP. استخدم مكتبة PHP API لدمج ملفات HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="دمج HTML في PHP" h2="مكتبة PHP عالية السرعة ومتعددة الأنظمة لدمج ملفات HTML باستخدام كود PHP" related="JPG,PNG,PDF,IMAGE,SVG,BMP,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="دمج HTML مع HTML في PHP" variant="code" %}}

باستخدام [** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) ، يمكنك دمج ملفات HTML بسرعة ببضعة سطور من التعليمات البرمجية

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود PHP لدمج HTML مع HTML" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename1 = 'file1.html';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }
    
    $pres->getSlides()->addFromHtml($contents1);
    
    $filename2 = 'file2.html';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $pres->getSlides()->addFromHtml($contents2);

    $pres->save("merged-html.html", SaveFormat::Html5);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="دمج HTML مع HTML باستخدام Aspose.Slides" %}}

[** Aspose.Slides for PHP عبر Java **](https://products.aspose.com/slides/ar/php-java/) هي مكتبة PHP قوية تُستخدم لإنشاء وتحويل ودمج ومعالجة العروض التقديمية وملفات HTML ووثائق أخرى. عندما تدمج HTML إلى HTML ، فأنت تدمج بشكل فعال المحتويات من وثيقتين للحصول على ملف HTML واحد. Aspose.Slides يسمح لك بدمج مستندات HTML بطرق مختلفة. يمكنك دمج HTML مع جميع نصوصها وتنسيقاتها وأنماطها وما إلى ذلك.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية دمج HTML في PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تثبيت ** Aspose.Slides for PHP عبر Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملفات HTML التي تريد دمجها.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ مستند HTML الناتج.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="مبني باستخدام Aspose.Slides" title="دمج ملفات HTML عبر الإنترنت" description="تطبيق Aspose.Slides Merger المجاني مبني باستخدام [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ar/php-java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات HTML الخاصة بك." button="افتح Aspose.Slides Merger" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يدمج Aspose.Slides الملفات قبل أن تكتب الكود.
- ارفع عدة ملفات HTML وادمجها في ملف واحد.
- نزّل النتيجة المدمجة كملف واحد.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="دمج الملفات الأخرى" subTitle="يمكنك أيضًا دمج الملفات بتنسيقات أخرى للحصول على ملف واحد" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
