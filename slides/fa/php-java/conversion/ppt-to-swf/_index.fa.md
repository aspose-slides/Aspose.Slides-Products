---
title: تبدیل PPT به SWF در PHP
weight: 2290
url: /fa/php-java/conversion/ppt-to-swf/ 
keywords: "Convert, PowerPoint, PPT, SWF, Presentation, PHP"
description: کد نمونه برای تبدیل PPT به SWF PHP. برای تبدیل دسته ای فایل های PPT به فایل های SWF از PowerPoint PHP API استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تبدیل PPT به SWF در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP برای تبدیل PPT به SWF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="تبدیل PPT به SWF در PHP" %}}

آیا نیاز به تبدیل فایل های PPT به SWF دارید؟ با استفاده از [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/fa/php-java/) هر توسعه دهنده می تواند تنها با چند خط کد PHP فرمت PPT را به SWF تبدیل کند. .

به عنوان یک API پردازش ارائه مدرن، Aspose.Slides برای PHP به سرعت SWF را از PPT ایجاد می کند. کیفیت تبدیل PPT به SWF را مستقیماً در [مرورگر](https://products.aspose.app/slides/conversion) خود آزمایش کنید. کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های PPT را به بسیاری از فرمت های محبوب تبدیل کنید.

با استفاده از دستور زیر می‌توانید کتابخانه را از [Composer](https://packagist.org/packages/aspose/slides) نصب کنید:

{{% blocks/products/pf/agp/code-block title="کنسول / ترمینال" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="نحوه تبدیل PPT به SWF در PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل فایل PPT به SWF با استفاده از PHP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل PPT را با نمونه ای از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
با تعیین مسیر فایل خروجی و SaveFormat.SWF به عنوان پارامتر، روش «save» را فراخوانی کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل PPT در مسیر مشخص شده ذخیره خواهد شد
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

{{% blocks/products/pf/agp/code-block title="این کد نمونه PPT به SWF تبدیل PHP را نشان می دهد" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.swf", SaveFormat::Swf);
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
 
{{% blocks/products/pf/agp/content h2="PPT را به عنوان SWF در PHP ذخیره کنید" %}}
از برنامه رایگان برای مشاهده نمایشی از فرآیند تبدیل PPT به SWF استفاده کنید. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPT to SWF" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید PPT را به بسیاری از فرمت‌های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="تصویر بیت مپ" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-fodp/" name="PPT TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-gif/" name="PPT TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-html/" name="PPT TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-jpg/" name="PPT TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-odp/" name="PPT TO ODP" description="فرمت ارائه اسناد باز" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-otp/" name="PPT TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-png/" name="PPT TO PNG" description="گرافیک شبکه قابل حمل" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-pot/" name="PPT TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-potm/" name="PPT TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-potx/" name="PPT TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-pps/" name="PPT TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="فایل ارائه ماکرو فعال" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="قالب ارائه XML را باز کنید" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-svg/" name="PPT TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/ppt-to-xps/" name="PPT TO XPS" description="مشخصات کاغذ XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}