---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل OTP إلى BMP في PHP
weight: 430
url: /ar/php-java/conversion/otp-to-bmp/ 
keywords: "Convert, PowerPoint, OTP, BMP, Presentation, PHP"
description: نموذج رمز من OTP إلى BMP تحويل PHP. استخدم PowerPoint PHP API لتحويل ملفات OTP إلى ملفات BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل OTP إلى BMP في PHP" h2="مكتبة PHP قوية في PowerPoint لتحويل OTP إلى BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل OTP إلى BMP في PHP" %}}

هل تحتاج إلى تحويل ملفات OTP إلى BMP برمجيًا؟ باستخدام [* Aspose.Slides for PHP عبر Java *](https://products.aspose.com/slides/ar/php-java/) يمكن لأي مطور تحويل OTP إلى تنسيق BMP ببضعة أسطر فقط من كود PHP .

كواجهة برمجة تطبيقات حديثة لمعالجة العروض التقديمية ، تقوم Aspose.Slides for PHP بإنشاء BMP من OTP بسرعة. اختبر جودة التحويل من OTP إلى BMP مباشرةً في [المتصفح](https://products.aspose.app/slides/conversion). تسمح لك مكتبة Aspose PowerPoint PPTX بتحويل ملفات OTP إلى العديد من التنسيقات الشائعة.

يمكنك تثبيت المكتبة من [Composer](https://packagist.org/packages/aspose/slides) باستخدام الأمر التالي:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="وحدة التحكم / المحطة" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="احفظ OTP كـ BMP في PHP" %}}

استخدم التطبيق المجاني لمشاهدة عرض توضيحي لعملية التحويل من OTP إلى BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="يوضح نموذج الشفرة هذا تحويل OTP إلى BMP PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".bmp");
        $imageio->write($bmp, "BMP", $javafile);
    }
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل OTP إلى BMP في PHP" intro="هذه هي خطوات تحويل ملف OTP إلى BMP باستخدام PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تحميل ملف OTP بنسخة من فئة العرض التقديمي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء طريقة "save" أثناء تحديد مسار ملف الإخراج & SaveFormat. BMP كمعلمات{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سيتم حفظ ملف OTP في المسار المحدد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="متطلبات النظام" intro="قبل تشغيل كود مصدر نموذج تحويل PHP ، تأكد من توفر المتطلبات الأساسية التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت PHP 7 ، أضف مسارًا إلى PHP إلى متغير النظام "PATH" واضبط "allow_url_include" على "تشغيل" في ملف "php.ini".{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت JRE 8. قم بتعيين متغير البيئة "JAVA_HOME" كمسار إلى موقع JRE المثبت.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت Apache Tomcat 8.0 (راجع [المزيد](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert OTP to BMP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل OTP إلى العديد من تنسيقات الملفات الأخرى. انظر التحويلات الأخرى المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-fodp/" name="OTP TO FODP" description="عرض تقديمي XML مسطح OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="تنسيق التبادل الرسومي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-html/" name="OTP TO HTML" description="لغة ترميز النصوص التشعبية" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="صورة JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="نموذج المستندات المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-png/" name="OTP TO PNG" description="رسومات الشبكة المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="ملف قالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-pps/" name="OTP TO PPS" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="افتح تنسيق عرض XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="الرسومات المتجهات قابلة لل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="تنسيق SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="تنسيق الصورة الموسومة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
