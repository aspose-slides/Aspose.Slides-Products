---
title: تحرير POTM في PHP
url: /ar/php-java/editor/potm/
keywords: تحرير POTM ، تحرير PowerPoint ، POTM ، PowerPoint ، PHP API ، مكتبة PHP
description: تحرير POTM في PHP. استخدم PHP Library API لتحرير ملفات POTM
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحرير POTM في PHP" h2="مكتبة PHP عالية السرعة ومتعددة الأنظمة للتحرير POTM باستخدام كود PHP" >}}

{{% blocks/products/pf/feature-page-section h2="تحرير POTM باستخدام Aspose.Slides" %}}

[** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) هي مكتبة PHP قوية لتحرير العروض التقديمية بسرعة وسهولة. يوفر للمستخدمين مجموعة واسعة من الميزات لمساعدتهم على إنشاء شرائح ذات مظهر احترافي في أي وقت من الأوقات على الإطلاق. باستخدام Aspose ، يمكن للمستخدمين تحرير النص وإضافة الصور والرسوم المتحركة والانتقالات إلى عرضهم التقديمي بالإضافة إلى تطبيق خيارات تنسيق مختلفة مثل نوع الخط واختيار اللون. بالإضافة إلى ذلك ، تقدم المكتبة الدعم لكل من ملفات PowerPoint (PPT) وتنسيقات OpenOffice Presentation (ODP) مما يجعل مشاركة العروض التقديمية عبر منصات مختلفة أسهل من أي وقت مضى دون ظهور أي مشاكل في التوافق. من خلال الاستفادة من قوة مكتبة Aspose عند إنشاء أو تعديل عرضك التقديمي التالي ، ستكون على يقين من أن شرائحك تبدو رائعة في كل مرة!
يمكنك تحرير ملف POTM عن طريق إضافة سطر جديد من النص إليه. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحرير POTM في PHP" %}}
باستخدام [** Aspose.Slides for PHP via Java **](https://products.aspose.com/slides/ar/php-java/) ، يمكنك إضافة سطر جديد من النص إلى مستند POTM بمجرد بضعة أسطر من التعليمات البرمجية.

{{% blocks/products/pf/agp/code-block title="كود PHP لتحرير POTM" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.potm", SaveFormat::Potm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحرير POTM في PHP" >}}

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
قم بتحميل العرض التقديمي POTM الذي تريد تحريره.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف سطرًا جديدًا من النص.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ الملف الذي تم تغييره.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="قم بتحرير الملفات الأخرى" subTitle="يمكنك أيضًا تحرير الملفات بتنسيقات أخرى" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}