---
title: PPSM را از طریق جاوا به PPTX تبدیل کنید
weight: 2550
url: /fa/java/conversion/ppsm-to-pptx/ 
description: نمونه کد تبدیل جاوا برای فرمت PPSM به فایل PPTX. از این کد مثال برای صدور پاورپوینت و ارائه های OpenOffice به PPTX در هر برنامه مبتنی بر وب یا دسکتاپ جاوا استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPSM را از طریق جاوا به PPTX تبدیل کنید" h2="تبدیل جاوا PPSM به PPTX برای تبدیل صفحات تک یا چند صفحه به PPTX با استفاده از کتابخانه جاوا در محل." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="نحوه تبدیل PPSM به PPTX با استفاده از جاوا" %}}

 برای رندر کردن PPSM به PPTX، از آن استفاده خواهیم کرد
 [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/)
 API که یک API تبدیل غنی، قدرتمند و آسان برای استفاده برای پلتفرم جاوا است. آخرین نسخه آن را می توانید مستقیماً از اینجا دانلود کنید
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 و با افزودن تنظیمات زیر به pom.xml آن را در پروژه مبتنی بر Maven خود نصب کنید.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="وابستگی" offSpacer="true" %}}

```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>version of aspose-slides API</version>
    <classifier>jdk17</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="مراحل تبدیل PPSM به PPTX از طریق جاوا" %}}

{{% blocks/products/pf/agp/text %}}

 توسعه دهندگان جاوا می توانند به راحتی فایل PPSM را تنها در چند خط کد به PPTX تبدیل کنند.

{{% /blocks/products/pf/agp/text %}}

1. فایل PPSM را با نمونه ای از کلاس Presentation بارگیری کنید
1. با مشخص کردن مسیر فایل خروجی و SaveFormat، متد Presentation.save را فراخوانی کنید.
1. فایل PPTX در مسیر مشخص شده ذخیره می شود

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 قبل از اجرای کد نمونه تبدیل جاوا، مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با محیط اجرای جاوا برای برنامه های کاربردی JSP/JSF و برنامه های دسکتاپ.
- آخرین نسخه Aspose.Slides برای جاوا را مستقیماً از Maven دریافت کنید.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="کد منبع تبدیل جاوا PPSM به PPTX" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("template.ppsm");
// save the presentation as PPTX
presentation.save("output.pptx", SaveFormat.Pptx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="برنامه رایگان برای تبدیل PPSM به PPTX" 
        sectionDescription="[برنامه رایگان MP4 To MP3 ما را امتحان کنید](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید PPSM را به بسیاری از فرمت‌های فایل دیگر از جمله تعداد کمی از آنها در زیر تبدیل کنید." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="فرمت تبادل گرافیکی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="گرافیک برداری مقیاس پذیر" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="فرمت SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="مشخصات کاغذ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}