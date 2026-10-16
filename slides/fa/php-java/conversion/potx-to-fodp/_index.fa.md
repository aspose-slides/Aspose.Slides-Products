---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل POTX به FODP در PHP
weight: 1280
url: /fa/php-java/conversion/potx-to-fodp/ 
keywords: "Convert, PowerPoint, POTX, FODP, Presentation, PHP"
description: کد نمونه برای تبدیل POTX به FODP PHP. برای تبدیل دسته ای فایل های POTX به فایل های FODP از PowerPoint PHP API استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل POTX به FODP در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP برای تبدیل POTX به FODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل POTX به FODP در PHP" %}}

آیا نیاز به تبدیل فایل های POTX به FODP دارید؟ با استفاده از [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/fa/php-java/) هر توسعه دهنده می تواند تنها با چند خط کد PHP فرمت POTX را به FODP تبدیل کند. .

به عنوان یک API پردازش ارائه مدرن، Aspose.Slides برای PHP به سرعت FODP را از POTX ایجاد می کند. کیفیت تبدیل POTX به FODP را مستقیماً در [مرورگر](https://products.aspose.app/slides/conversion) خود آزمایش کنید. کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های POTX را به بسیاری از فرمت های محبوب تبدیل کنید.

با استفاده از دستور زیر می‌توانید کتابخانه را از [Composer](https://packagist.org/packages/aspose/slides) نصب کنید:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="کنسول / ترمینال" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POTX را به عنوان FODP در PHP ذخیره کنید" %}}

از برنامه رایگان برای مشاهده نمایشی از فرآیند تبدیل POTX به FODP استفاده کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="این کد نمونه POTX به FODP تبدیل PHP را نشان می دهد" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $pres->save("output.fodp", SaveFormat::Fodp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل POTX به FODP در PHP" intro="این مراحل برای تبدیل فایل POTX به FODP با استفاده از PHP است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل POTX را با نمونه ای از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با تعیین مسیر فایل خروجی و SaveFormat.FODP به عنوان پارامتر، روش «save» را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل POTX در مسیر مشخص شده ذخیره خواهد شد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="سیستم مورد نیاز" intro="قبل از اجرای کد منبع نمونه تبدیل PHP، مطمئن شوید که پیش نیازهای زیر را دارید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7 را نصب کنید، مسیر PHP را به متغیر «PATH» سیستم اضافه کنید و «allow_url_include» را در فایل «php.ini» روی «روشن» قرار دهید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE را نصب کنید. 8. متغیر محیط «JAVA_HOME» را به عنوان مسیری به مکان نصب شده JRE تنظیم کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0 را نصب کنید (به [بیشتر](https://docs.aspose.com/slides/php-java/installation/) مراجعه کنید).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POTX to FODP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید POTX را به بسیاری از فرمت‌های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-bmp/" name="POTX TO BMP" description="تصویر بیت مپ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-gif/" name="POTX TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-html/" name="POTX TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-jpg/" name="POTX TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-odp/" name="POTX TO ODP" description="فرمت ارائه اسناد باز" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-otp/" name="POTX TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pdf/" name="POTX TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-png/" name="POTX TO PNG" description="گرافیک شبکه قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pot/" name="POTX TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-potm/" name="POTX TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pps/" name="POTX TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-ppt/" name="POTX TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="فایل ارائه ماکرو فعال" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pptx/" name="POTX TO PPTX" description="قالب ارائه XML را باز کنید" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-svg/" name="POTX TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-swf/" name="POTX TO SWF" description="فرمت SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-tiff/" name="POTX TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-xps/" name="POTX TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
