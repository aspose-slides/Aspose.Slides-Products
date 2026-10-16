---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل ODP به GIF از طریق جاوا
weight: 1180
url: /fa/java/conversion/odp-to-gif/ 
description: نمونه کد تبدیل جاوا برای فرمت ODP به فایل GIF. از این کد مثال برای صادرات پاورپوینت و ارائه های OpenOffice به GIF در هر برنامه مبتنی بر وب یا دسکتاپ جاوا استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل ODP به GIF از طریق جاوا" h2="تبدیل ODP به GIF جاوا برای تبدیل صفحات منفرد یا چندگانه به GIF با استفاده از کتابخانه داخلی جاوا."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه تبدیل ODP به GIF با استفاده از جاوا" %}}

برای ارائه ODP به GIF، از
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد منبع تبدیل جاوا ODP به GIF" >}}
```cs
// load ODP with Aspose.Slides
Presentation presentation = new Presentation("template.odp");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type GIF for every slide
  File outputfile = new File(sld.getSlideNumber() + ".gif");
  
  // save the slide image to disk
  ImageIO.write(bi, "gif", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل تبدیل ODP به GIF از طریق جاوا" intro="توسعه دهندگان جاوا می توانند به راحتی فایل ODP را تنها در چند خط کد به GIF تبدیل کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با یک نمونه از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}در هر اسلاید در ارائه تکرار کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با هر تکرار یک تصویر در مقیاس کامل به عنوان Bitmap ایجاد کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روش Bitmap.save را با پسوند فایل GIF و ImageFormat فراخوانی کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد نمونه تبدیل جاوا، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با محیط اجرای جاوا برای برنامه های کاربردی JSP/JSF و برنامه های دسکتاپ.
- آخرین نسخه Aspose.Slides برای جاوا را مستقیماً از Maven دریافت کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="برنامه رایگان برای تبدیل ODP به GIF"
  description="[برنامه رایگان MP4 To MP3 ما را امتحان کنید](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="شما همچنین می توانید ODP را به بسیاری از فرمت های فایل دیگر از جمله تعداد کمی از آنها در زیر تبدیل کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-html/" name="ODP TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-otp/" name="ODP TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-png/" name="ODP TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-pot/" name="ODP TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-potm/" name="ODP TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-potx/" name="ODP TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-pps/" name="ODP TO PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-svg/" name="ODP TO SVG" description="گرافیک برداری مقیاس پذیر" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-swf/" name="ODP TO SWF" description="فرمت SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/odp-to-xps/" name="ODP TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
