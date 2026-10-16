---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل PPTM به ODP در PHP
weight: 2370
url: /fa/php-java/conversion/pptm-to-odp/ 
keywords: "Convert, PowerPoint, PPTM, ODP, Presentation, PHP"
description: کد نمونه برای تبدیل PPTM به ODP PHP. برای تبدیل دسته ای فایل های PPTM به فایل های ODP از PowerPoint PHP API استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل PPTM به ODP در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP برای تبدیل PPTM به ODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل PPTM به ODP در PHP" %}}

آیا نیاز به تبدیل فایل های PPTM به ODP دارید؟ با استفاده از [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/fa/php-java/) هر توسعه دهنده می تواند تنها با چند خط کد PHP فرمت PPTM را به ODP تبدیل کند. .

به عنوان یک API پردازش ارائه مدرن، Aspose.Slides برای PHP به سرعت ODP را از PPTM ایجاد می کند. کیفیت تبدیل PPTM به ODP را مستقیماً در [مرورگر](https://products.aspose.app/slides/conversion) خود آزمایش کنید. کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های PPTM را به بسیاری از فرمت های محبوب تبدیل کنید.

با استفاده از دستور زیر می‌توانید کتابخانه را از [Composer](https://packagist.org/packages/aspose/slides) نصب کنید:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="کنسول / ترمینال" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTM را به عنوان ODP در PHP ذخیره کنید" %}}

از برنامه رایگان برای مشاهده نمایشی از فرآیند تبدیل PPTM به ODP استفاده کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="این کد نمونه PPTM به ODP تبدیل PHP را نشان می دهد" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.odp", SaveFormat::Odp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل PPTM به ODP در PHP" intro="این مراحل برای تبدیل فایل PPTM به ODP با استفاده از PHP است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTM را با نمونه ای از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با تعیین مسیر فایل خروجی و SaveFormat.ODP به عنوان پارامتر، روش «save» را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTM در مسیر مشخص شده ذخیره خواهد شد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="سیستم مورد نیاز" intro="قبل از اجرای کد منبع نمونه تبدیل PHP، مطمئن شوید که پیش نیازهای زیر را دارید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7 را نصب کنید، مسیر PHP را به متغیر «PATH» سیستم اضافه کنید و «allow_url_include» را در فایل «php.ini» روی «روشن» قرار دهید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE را نصب کنید. 8. متغیر محیط «JAVA_HOME» را به عنوان مسیری به مکان نصب شده JRE تنظیم کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0 را نصب کنید (به [بیشتر](https://docs.aspose.com/slides/php-java/installation/) مراجعه کنید).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to ODP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید PPTM را به بسیاری از فرمت‌های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="تصویر بیت مپ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="گرافیک شبکه قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="قالب ارائه XML را باز کنید" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="فرمت SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
