---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: POTM را از طریق جاوا به POTX تبدیل کنید
weight: 170
url: /fa/java/conversion/potm-to-potx/ 
description: نمونه کد تبدیل جاوا برای فرمت POTM به فایل POTX. از این کد مثال برای صدور پاورپوینت و ارائه های OpenOffice به POTX در هر برنامه مبتنی بر وب یا دسکتاپ جاوا استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="POTM را از طریق جاوا به POTX تبدیل کنید" h2="تبدیل جاوا POTM به POTX برای تبدیل صفحات تک یا چند صفحه به POTX با استفاده از کتابخانه جاوا در محل."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه تبدیل POTM به POTX با استفاده از جاوا" %}}

برای رندر کردن POTM به POTX، از آن استفاده خواهیم کرد
 [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/)
 API که یک API تبدیل غنی، قدرتمند و آسان برای استفاده برای پلتفرم جاوا است. آخرین نسخه آن را می توانید مستقیماً از اینجا دانلود کنید
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 و با افزودن تنظیمات زیر به pom.xml آن را در پروژه مبتنی بر Maven خود نصب کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="مخزن" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="وابستگی" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد منبع تبدیل جاوا POTM به POTX" >}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("template.potm");
// save the presentation as POTX
presentation.save("output.potx", SaveFormat.Potx);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل تبدیل POTM به POTX از طریق جاوا" intro="توسعه دهندگان جاوا می توانند به راحتی فایل POTM را تنها در چند خط کد به POTX تبدیل کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل POTM را با نمونه ای از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با مشخص کردن مسیر فایل خروجی و SaveFormat، متد Presentation.save را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل POTX در مسیر مشخص شده ذخیره می شود{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد نمونه تبدیل جاوا، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با محیط اجرای جاوا برای برنامه های کاربردی JSP/JSF و برنامه های دسکتاپ.
- آخرین نسخه Aspose.Slides برای جاوا را مستقیماً از Maven دریافت کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="برنامه رایگان برای تبدیل POTM به POTX"
  description="[برنامه رایگان Video ما را امتحان کنید](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="شما همچنین می توانید POTM را به بسیاری از فرمت های فایل دیگر از جمله تعداد کمی از آنها در زیر تبدیل کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-bmp/" name="POTM TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-gif/" name="POTM TO GIF" description="فرمت تبادل گرافیکی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-html/" name="POTM TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-odp/" name="POTM TO ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-otp/" name="POTM TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-pdf/" name="POTM TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-png/" name="POTM TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-pot/" name="POTM TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-pps/" name="POTM TO PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-ppt/" name="POTM TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-svg/" name="POTM TO SVG" description="گرافیک برداری مقیاس پذیر" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-swf/" name="POTM TO SWF" description="فرمت SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/potm-to-xps/" name="POTM TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
