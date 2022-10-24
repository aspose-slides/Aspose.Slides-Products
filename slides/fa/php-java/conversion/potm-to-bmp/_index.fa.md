---
title: تبدیل POTM به BMP در PHP
weight: 1060
url: /fa/php-java/conversion/potm-to-bmp/ 
keywords: "Convert, PowerPoint, POTM, BMP, Presentation, PHP"
description: کد نمونه برای تبدیل POTM به BMP PHP. برای تبدیل دسته ای فایل های POTM به فایل های BMP از PowerPoint PHP API استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تبدیل POTM به BMP در PHP" h2="کتابخانه قدرتمند پاورپوینت PHP برای تبدیل POTM به BMP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="تبدیل POTM به BMP در PHP" %}}

آیا نیاز به تبدیل فایل های POTM به BMP دارید؟ با استفاده از [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/fa/php-java/) هر توسعه دهنده می تواند تنها با چند خط کد PHP فرمت POTM را به BMP تبدیل کند. .

به عنوان یک API پردازش ارائه مدرن، Aspose.Slides برای PHP به سرعت BMP را از POTM ایجاد می کند. کیفیت تبدیل POTM به BMP را مستقیماً در [مرورگر](https://products.aspose.app/slides/conversion) خود آزمایش کنید. کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های POTM را به بسیاری از فرمت های محبوب تبدیل کنید.

با استفاده از دستور زیر می‌توانید کتابخانه را از [Composer](https://packagist.org/packages/aspose/slides) نصب کنید:

{{% blocks/products/pf/agp/code-block title="کنسول / ترمینال" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="نحوه تبدیل POTM به BMP در PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل فایل POTM به BMP با استفاده از PHP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل POTM را با نمونه ای از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
با تعیین مسیر فایل خروجی و SaveFormat.BMP به عنوان پارامتر، روش «save» را فراخوانی کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل POTM در مسیر مشخص شده ذخیره خواهد شد
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

{{% blocks/products/pf/agp/code-block title="این کد نمونه POTM به BMP تبدیل PHP را نشان می دهد" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
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
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="POTM را به عنوان BMP در PHP ذخیره کنید" %}}
از برنامه رایگان برای مشاهده نمایشی از فرآیند تبدیل POTM به BMP استفاده کنید. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert POTM to BMP" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید POTM را به بسیاری از فرمت‌های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-odp/" name="POTM TO ODP" description="فرمت ارائه اسناد باز" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="گرافیک شبکه قابل حمل" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="فایل ارائه ماکرو فعال" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="قالب ارائه XML را باز کنید" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="فرمت SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="مشخصات کاغذ XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}