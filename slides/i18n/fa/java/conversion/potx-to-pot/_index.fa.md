---
title: تبدیل POTX به POT از طریق جاوا
weight: 50
url: /fa/java/conversion/potx-to-pot/ 
description: نمونه کد تبدیل جاوا برای فرمت POTX به فایل POT. از این کد مثال برای صادرات پاورپوینت و ارائه های OpenOffice به POT در هر برنامه مبتنی بر وب یا دسکتاپ جاوا استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تبدیل POTX به POT از طریق جاوا" h2="تبدیل POTX به POT جاوا برای تبدیل صفحات منفرد یا چندگانه به POT با استفاده از کتابخانه داخلی جاوا." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="نحوه تبدیل POTX به POT با استفاده از جاوا" %}}

 به منظور رندر POTX به POT، ما استفاده خواهیم کرد
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 API که یک API تبدیل غنی، قدرتمند و آسان برای استفاده برای پلتفرم جاوا است. آخرین نسخه آن را می توانید مستقیماً از اینجا دانلود کنید
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 و با افزودن تنظیمات زیر به pom.xml آن را در پروژه مبتنی بر Maven خود نصب کنید.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="وابستگی" offSpacer="true" %}}

```cs
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

{{% blocks/products/pf/agp/feature-section-col title="مراحل تبدیل POTX به POT از طریق جاوا" %}}

{{% blocks/products/pf/agp/text %}}

 توسعه دهندگان جاوا می توانند به راحتی فایل POTX را تنها در چند خط کد به POT تبدیل کنند.

{{% /blocks/products/pf/agp/text %}}

1. فایل POTX را با یک نمونه از کلاس Presentation بارگیری کنید
1. با مشخص کردن مسیر فایل خروجی و SaveFormat، متد Presentation.save را فراخوانی کنید.
1. فایل POT در مسیر مشخص شده ذخیره می شود

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 قبل از اجرای کد نمونه تبدیل جاوا، مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با محیط اجرای جاوا برای برنامه های کاربردی JSP/JSF و برنامه های دسکتاپ.
- آخرین نسخه Aspose.Slides برای جاوا را مستقیماً از Maven دریافت کنید.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="کد منبع تبدیل جاوا POTX به POT" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("template.potx");
// save the presentation as POT
presentation.save("output.pot", SaveFormat.Pot);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="POTX to POT Conversion Live Demos" sectionDescription="[Convert POTX to POT](https://products.aspose.app/slides/conversion/potx-to-pot) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POTX file, it will be converted instantly to POT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="کتابخانه دستکاری ارائه جاوا" %}}

 Slides and Presentation API را می توان برای خواندن، نوشتن، دستکاری و تبدیل اسناد Microsoft PowerPoint به PDF، XPS، HTML، TIFF، ODP و فرمت های مختلف دیگر استفاده کرد. می توان فایل های جدید را از ابتدا ایجاد کرد و آن ها را در قالب های پشتیبانی شده مربوطه ذخیره کرد. Aspose.Slides یک API مستقل برای ایجاد، تجزیه یا دستکاری ارائه ها، اسلایدها و عناصر است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice وابسته نیست.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" >}}

Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. This format was created to replace the POT file format that is based on the binary file format and is supported with PowerPoint 97-2003. The files generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" >}}

Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید POTX را به بسیاری از فرمت‌های فایل دیگر از جمله تعداد کمی از آنها در زیر تبدیل کنید." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-bmp/" name="POTX TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-gif/" name="POTX TO GIF" description="فرمت تبادل گرافیکی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-html/" name="POTX TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-odp/" name="POTX TO ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-otp/" name="POTX TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-pdf/" name="POTX TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-png/" name="POTX TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-potm/" name="POTX TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-pps/" name="POTX TO PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-ppt/" name="POTX TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-pptx/" name="POTX TO PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-svg/" name="POTX TO SVG" description="گرافیک برداری مقیاس پذیر" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-swf/" name="POTX TO SWF" description="فرمت SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-tiff/" name="POTX TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/potx-to-xps/" name="POTX TO XPS" description="مشخصات کاغذ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}