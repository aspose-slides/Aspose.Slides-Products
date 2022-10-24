---
title: تبدیل POTX به PPTX در PHP
weight: 1430
url: /fa/php-java/conversion/potx-to-pptx/ 
keywords: "Convert, PowerPoint, POTX, PPTX, Presentation, PHP"
description: کد نمونه برای تبدیل POTX به PPTX PHP. برای تبدیل دسته ای فایل های POTX به فایل های PPTX از PowerPoint PHP API استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تبدیل POTX به PPTX در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP برای تبدیل POTX به PPTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="تبدیل POTX به PPTX در PHP" %}}

آیا نیاز به تبدیل فایل های POTX به PPTX دارید؟ با استفاده از [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/fa/php-java/) هر توسعه دهنده می تواند تنها با چند خط کد PHP فرمت POTX را به PPTX تبدیل کند. .

به عنوان یک API پردازش ارائه مدرن، Aspose.Slides برای PHP به سرعت PPTX را از POTX ایجاد می کند. کیفیت تبدیل POTX به PPTX را مستقیماً در [مرورگر](https://products.aspose.app/slides/conversion) خود آزمایش کنید. کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های POTX را به بسیاری از فرمت های محبوب تبدیل کنید.

با استفاده از دستور زیر می‌توانید کتابخانه را از [Composer](https://packagist.org/packages/aspose/slides) نصب کنید:

{{% blocks/products/pf/agp/code-block title="کنسول / ترمینال" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="نحوه تبدیل POTX به PPTX در PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل فایل POTX به PPTX با استفاده از PHP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل POTX را با نمونه ای از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
با تعیین مسیر فایل خروجی و SaveFormat.PPTX به عنوان پارامتر، روش «save» را فراخوانی کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل POTX در مسیر مشخص شده ذخیره خواهد شد
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 قبل از اجرای کد منبع نمونه تبدیل PHP، مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

1. PHP 7 را نصب کنید، مسیر PHP را به متغیر «PATH» سیستم اضافه کنید و «allow_url_include» را در فایل «php.ini» روی «روشن» قرار دهید.
1. JRE را نصب کنید. 8. متغیر محیط «JAVA_HOME» را به عنوان مسیری به مکان نصب شده JRE تنظیم کنید.
1. Apache Tomcat 8.0 را نصب کنید (به [بیشتر](https://docs.aspose.com/slides/php-java/installation/) مراجعه کنید). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="این کد نمونه POTX به PPTX تبدیل PHP را نشان می دهد" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="POTX را به عنوان PPTX در PHP ذخیره کنید" %}}
از برنامه رایگان برای مشاهده نمایشی از فرآیند تبدیل POTX به PPTX استفاده کنید. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert POTX to PPTX" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید POTX را به بسیاری از فرمت‌های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-bmp/" name="POTX TO BMP" description="تصویر بیت مپ" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-fodp/" name="POTX TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-gif/" name="POTX TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-html/" name="POTX TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-jpg/" name="POTX TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-odp/" name="POTX TO ODP" description="فرمت ارائه اسناد باز" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-otp/" name="POTX TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pdf/" name="POTX TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-png/" name="POTX TO PNG" description="گرافیک شبکه قابل حمل" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pot/" name="POTX TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-potm/" name="POTX TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pps/" name="POTX TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-ppt/" name="POTX TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="فایل ارائه ماکرو فعال" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-svg/" name="POTX TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-swf/" name="POTX TO SWF" description="فرمت SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-tiff/" name="POTX TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potx-to-xps/" name="POTX TO XPS" description="مشخصات کاغذ XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}