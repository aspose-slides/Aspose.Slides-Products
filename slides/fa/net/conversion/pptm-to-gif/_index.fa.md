---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل PPTM به GIF از طریق C#
weight: 8680
url: /fa/net/conversion/pptm-to-gif/ 
description: کد نمونه برای تبدیل PPTM به GIF C#. از کد نمونه API برای تبدیل دسته ای فایل های PPTM به GIF در VB.NET، Asp.NET یا هر برنامه مبتنی بر NET استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل PPTM به GIF از طریق C#" h2="فایل‌های PowerPoint® PPTM را به GIF در پلتفرم‌های NET Framework، NET Core، Windows Azure، Mono یا Xamarin صادر کنید."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه تبدیل PPTM به GIF با استفاده از C#" %}}

برای تبدیل PPTM به GIF، ما استفاده خواهیم کرد
 [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net)
 API که یک API غنی از ویژگی، قدرتمند و آسان برای دستکاری و تبدیل اسناد برای پلتفرم C# است. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 مدیر بسته، جستجو کنید
 Aspose.Slides
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="فرمان کنسول Package Manager" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="این کد نمونه تبدیل PPTM به GIF C# را نشان می دهد" >}}
```cs
using (var presentation = new Presentation("template.pptm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in GIF format
        bitmap.Save(string.Format("Slide_{0}.gif", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Gif);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل تبدیل PPTM به GIF از طریق C#" intro="توسعه دهندگان دات نت می توانند به راحتی فایل های PPTM را تنها در چند خط کد بارگیری و به GIF تبدیل کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTM را با نمونه ای از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}در هر اسلاید در ارائه تکرار کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با هر تکرار یک تصویر در مقیاس کامل به عنوان Bitmap ایجاد کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روش Bitmap.Save را با پسوند فایل GIF و ImageFormat.Gif به عنوان پارامتر فراخوانی کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد منبع نمونه تبدیل دات نت، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin.
- محیط توسعه مانند Microsoft Visual Studio.
- Aspose.Slides برای DLL NET که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="برنامه رایگان برای تبدیل PPTM به GIF"
  description="[برنامه رایگان MP4 To MP3 ما را امتحان کنید](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید PPTM را به بسیاری از فرمت‌های فایل دیگر از جمله تعداد کمی از آنها در زیر تبدیل کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="فرمت متافایل پیشرفته" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-html/" name="PPTM TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-png/" name="PPTM TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-pot/" name="PPTM TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="گرافیک برداری مقیاس پذیر" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="فرمت SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
