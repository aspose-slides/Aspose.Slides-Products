---
lastmod: 2023-02-06
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحرير PPT في PHP
url: /ar/php-java/editor/ppt/
keywords: تحرير PPT ، تحرير PowerPoint ، PPT ، PowerPoint ، PHP API ، مكتبة PHP
description: تحرير PPT في PHP. استخدم PHP Library API لتحرير ملفات PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحرير PPT في PHP" h2="مكتبة PHP عالية السرعة ومتعددة الأنظمة للتحرير PPT باستخدام كود PHP" related="FODP,HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحرير PPT في PHP" variant="code" %}}

باستخدام [** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) ، يمكنك إضافة سطر جديد من النص إلى مستند PPT بمجرد بضعة أسطر من التعليمات البرمجية.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود PHP لتحرير PPT" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحرير PPT باستخدام Aspose.Slides" %}}

[** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) هي مكتبة PHP قوية لتحرير العروض التقديمية بسرعة وسهولة. يوفر للمستخدمين مجموعة واسعة من الميزات لمساعدتهم على إنشاء شرائح ذات مظهر احترافي في أي وقت من الأوقات على الإطلاق. باستخدام Aspose ، يمكن للمستخدمين تحرير النص وإضافة الصور والرسوم المتحركة والانتقالات إلى عرضهم التقديمي بالإضافة إلى تطبيق خيارات تنسيق مختلفة مثل نوع الخط واختيار اللون. بالإضافة إلى ذلك ، تقدم المكتبة الدعم لكل من ملفات PowerPoint (PPT) وتنسيقات OpenOffice Presentation (ODP) مما يجعل مشاركة العروض التقديمية عبر منصات مختلفة أسهل من أي وقت مضى دون ظهور أي مشاكل في التوافق. من خلال الاستفادة من قوة مكتبة Aspose عند إنشاء أو تعديل عرضك التقديمي التالي ، ستكون على يقين من أن شرائحك تبدو رائعة في كل مرة!
يمكنك تحرير ملف PPT عن طريق إضافة سطر جديد من النص إليه.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحرير PPT في PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تثبيت ** Aspose.Slides for PHP عبر Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل العرض التقديمي PPT الذي تريد تحريره.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف سطرًا جديدًا من النص.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف الذي تم تغييره.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="مبني باستخدام Aspose.Slides" title="تحرير ملفات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Editor المجاني مبني باستخدام [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ar/php-java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Editor" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يتعامل Aspose.Slides مع ملفاتك قبل كتابة الكود.
- ارفع ملفات PPTX وحررها فورًا.
- احفظ الملف المحرر وقم بتنزيله.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="قم بتحرير الملفات الأخرى" subTitle="يمكنك أيضًا تحرير الملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/editor/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
