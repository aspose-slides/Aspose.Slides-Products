---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PDF إلى PPT في PHP
weight: 780
url: /ar/php-java/conversion/pdf-to-ppt/ 
keywords: "Convert, PowerPoint, PDF, PPT, Presentation, PHP"
description: نموذج رمز من PDF إلى PPT تحويل PHP. استخدم PowerPoint PHP API لتحويل ملفات PDF إلى ملفات PPT.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PDF إلى PPT في PHP" h2="مكتبة PHP قوية في PowerPoint لتحويل PDF إلى PPT"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PDF إلى PPT في PHP" %}}

هل تحتاج إلى تحويل ملفات PDF إلى PPT برمجيًا؟ باستخدام [* Aspose.Slides for PHP عبر Java *](https://products.aspose.com/slides/ar/php-java/) يمكن لأي مطور تحويل PDF إلى تنسيق PPT ببضعة أسطر فقط من كود PHP .

كواجهة برمجة تطبيقات حديثة لمعالجة العروض التقديمية ، تقوم Aspose.Slides for PHP بإنشاء PPT من PDF بسرعة. اختبر جودة التحويل من PDF إلى PPT مباشرةً في [المتصفح](https://products.aspose.app/slides/conversion). تسمح لك مكتبة Aspose PowerPoint PPTX بتحويل ملفات PDF إلى العديد من التنسيقات الشائعة.

يمكنك تثبيت المكتبة من [Composer](https://packagist.org/packages/aspose/slides) باستخدام الأمر التالي:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="وحدة التحكم / المحطة" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="احفظ PDF كـ PPT في PHP" %}}

استخدم التطبيق المجاني لمشاهدة عرض توضيحي لعملية التحويل من PDF إلى PPT.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="يوضح نموذج الشفرة هذا تحويل PDF إلى PPT PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    $pres->save("output.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PDF إلى PPT في PHP" intro="هذه هي خطوات تحويل ملف PDF إلى PPT باستخدام PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تحميل ملف PDF بنسخة من فئة العرض التقديمي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء طريقة "save" أثناء تحديد مسار ملف الإخراج & SaveFormat. PPT كمعلمات{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سيتم حفظ ملف PDF في المسار المحدد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="متطلبات النظام" intro="قبل تشغيل كود مصدر نموذج تحويل PHP ، تأكد من توفر المتطلبات الأساسية التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت PHP 7 ، أضف مسارًا إلى PHP إلى متغير النظام "PATH" واضبط "allow_url_include" على "تشغيل" في ملف "php.ini".{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت JRE 8. قم بتعيين متغير البيئة "JAVA_HOME" كمسار إلى موقع JRE المثبت.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت Apache Tomcat 8.0 (راجع [المزيد](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="مبني باستخدام Aspose.Slides" title="تحويل PDF إلى PPT عبر الإنترنت" description="تطبيق Aspose.Slides Conversion المجاني مبني باستخدام [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ar/php-java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PDF الخاصة بك." button="افتح Aspose.Slides Conversion" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" upload="أفلت ملفك أو ارفعه" saveAs="حفظ بتنسيق" convert="تحويل" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحوّل Aspose.Slides الملفات قبل أن تكتب الكود.
- ارفع ملفات PDF واحفظها بتنسيق PPT.
- نزّل النتيجة أو حوّل المزيد من الملفات.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PDF إلى العديد من تنسيقات الملفات الأخرى. انظر التحويلات الأخرى المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="سيب" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-fodp/" name="PDF TO FODP" description="عرض تقديمي XML مسطح OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="تنسيق التبادل الرسومي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-html/" name="PDF TO HTML" description="لغة ترميز النصوص التشعبية" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="صورة JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="تنسيق OpenDocument القياسي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="رسومات الشبكة المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-potm/" name="PDF TO POTM" description="ملف قالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-pps/" name="PDF TO PPS" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="افتح تنسيق عرض XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="الرسومات المتجهات قابلة لل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="تنسيق SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="تنسيق الصورة الموسومة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
