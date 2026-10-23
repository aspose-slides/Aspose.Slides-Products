---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: فایل های PPTM را از طریق دات نت ویرایش کنید
url: /fa/net/editor/pptm/ 
description: کد منبع سی شارپ برای ویرایش سند PPTM در پلتفرم‌های NET Framework، NET Core، Windows Azure، Mono یا Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ویرایش فرمت های PPTM در سی شارپ" h2="ویرایش سند PPTM بومی و با کارایی بالا با استفاده از Aspose.Slides سمت سرور برای API های دات نت، بدون استفاده از هیچ نرم افزاری مانند Microsoft یا Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه ویرایش فایل PPTM با استفاده از سی شارپ" %}}

به منظور ویرایش فایل PPTM، از <a href="https://products.aspose.com/slides/fa/net">Aspose.Slides برای .NET</a> API استفاده می کنیم که یک ویژگی غنی و قدرتمند است. و آسان برای استفاده از API برای پلت فرم C# برای هر ویرایشگر. مدیر بسته <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> را باز کنید، <b>Aspose.Slides</b> را جستجو کرده و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="فرمان" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ویرایش فایل های PPTM - C#" >}}
```cs
using var presentation = new Presentation("document.pptm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pptm", SaveFormat.Pptm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل ویرایش فایل های PPTM در سی شارپ" intro="یک ویرایش اولیه سند با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net) API ها را می توان تنها با چند خط کد انجام داد." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTM را با یک شیء `Presentation` بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از طریق متغیرها به اسلاید و شکل مورد نظر دسترسی پیدا کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متن را از طریق `TextFrame` به‌روزرسانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائهٔ ویرایش‌شده را با `SaveFormat.Pptm` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="API های ما در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می شوند. لطفا قبل از اجرای کد زیر، از داشتن پیش نیازهای زیر در سیستم خود اطمینان حاصل کنید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin Platforms
- محیط توسعه مانند Microsoft Visual Studio
- Aspose.Slides برای DLL.NET که در پروژه شما ارجاع داده شده است - از NuGet با استفاده از دکمه دانلود در بالا نصب کنید

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="ساخته شده با Aspose.Slides" title="ویرایش آنلاین فایل‌های PPTX" description="برنامه رایگان Aspose.Slides Editor با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Editor" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌های شما را پردازش می‌کند.
- فایل‌های PPTX خود را بارگذاری کنید و فوراً ویرایش کنید.
- فایل ویرایش‌شده را ذخیره و دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

Files with PPTM extension are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. They are similar to PPTX files with the difference that the lateral can't execute macros though they can contain macros. PPTM files can be edited by opening them in Microsoft PowerPoint and updating the contents. Another similar format is PPSM but it is read-only by default and starts the slideshow when opened. PPTM, like PPTX, contains slides for different presentation elements like text, images, videos, graphs and other related material.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
