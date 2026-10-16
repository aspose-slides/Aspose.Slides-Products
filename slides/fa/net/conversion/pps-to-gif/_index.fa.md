---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل PPS به GIF از طریق C#
weight: 4000
url: /fa/net/conversion/pps-to-gif/ 
description: کد نمونه برای تبدیل PPS به GIF C#. از کد نمونه API برای تبدیل دسته ای فایل های PPS به GIF در VB.NET، Asp.NET یا هر برنامه مبتنی بر دات نت استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل PPS به GIF از طریق C#" h2="فایل‌های PowerPoint® PPS را به GIF در پلتفرم‌های NET Framework، NET Core، Windows Azure، Mono یا Xamarin صادر کنید."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه تبدیل PPS به GIF با استفاده از سی شارپ" %}}

برای تبدیل PPS به GIF، ما استفاده خواهیم کرد
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="این کد نمونه تبدیل PPS به GIF C# را نشان می دهد" >}}
```cs
using (var presentation = new Presentation("template.pps"))
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل تبدیل PPS به GIF از طریق C#" intro="توسعه دهندگان دات نت می توانند به راحتی فایل های PPS را تنها در چند خط کد به GIF بارگیری و تبدیل کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPS را با یک نمونه از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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
  title="برنامه رایگان برای تبدیل PPS به GIF"
  description="[برنامه رایگان Editor ما را امتحان کنید](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید PPS را به بسیاری از فرمت‌های فایل دیگر از جمله چند مورد در زیر تبدیل کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-bmp/" name="PPS TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-emf/" name="PPS TO EMF" description="فرمت متافایل پیشرفته" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-html/" name="PPS TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-odp/" name="PPS TO ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-otp/" name="PPS TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-pdf/" name="PPS TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-png/" name="PPS TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-pot/" name="PPS TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-potm/" name="PPS TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-potx/" name="PPS TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-ppt/" name="PPS TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-svg/" name="PPS TO SVG" description="گرافیک برداری مقیاس پذیر" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-swf/" name="PPS TO SWF" description="فرمت SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/conversion/pps-to-xps/" name="PPS TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
