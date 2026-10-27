---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: مشاهده POTX در C#
keywords: مشاهده POTX, باز کردن POTX, نمایشگر POTX, POTX, PowerPoint, C# API, کتابخانه .NET
weight: 5740
url: /fa/net/viewer/potx/ 
description: فایل‌های POTX را در C# مشاهده کنید. با Aspose.Slides for .NET فایل‌های ارائه را باز کنید و به‌صورت HTML ذخیره کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="مشاهده POTX در C#" h2="API زبان C# برای باز کردن فایل‌های POTX و ذخیره آن‌ها به‌صورت HTML واکنش‌گرا."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="مشاهده POTX با Aspose.Slides" %}}

برای مشاهده فایل‌های POTX از API [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) استفاده کنید؛ یک API قدرتمند، کامل و آسان برای C#. مدیر بسته [NuGet](https://www.nuget.org/packages/aspose.slides.net) را باز کنید، **Aspose.Slides** را جستجو و نصب کنید. همچنین می‌توانید دستور زیر را در Package Manager Console اجرا کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="دستور Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

با [**Aspose.Slides for .NET**](/slides/fa/net/) می‌توانید یک فایل POTX را بارگذاری کرده و با چند خط کد به‌صورت HTML واکنش‌گرا ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد C# برای مشاهده POTX" >}}
```cs
using var presentation = new Presentation("presentation.potx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه مشاهده POTX در C#" intro="Aspose.Slides به توسعه‌دهندگان امکان می‌دهد فایل‌های POTX را تنها با چند خط کد مشاهده کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** را نصب کنید. [**نصب**](https://docs.aspose.com/slides/net/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به‌عنوان مرجع به پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل `POTX` را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک شیء `ResponsiveHtmlController` برای خروجی HTML واکنش‌گرا ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک شیء `HtmlOptions` ایجاد کنید و ویژگی `HtmlFormatter` را تنظیم کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل POTX را با `SaveFormat.Html` به‌صورت HTML ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="پیش‌نیازهای سیستم" intro="Aspose.Slides for .NET از همه سیستم‌عامل‌های اصلی پشتیبانی می‌کند. مطمئن شوید پیش‌نیازهای زیر را دارید." %}}

- Microsoft Windows یا سیستم‌عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin
- یک محیط توسعه مانند Microsoft Visual Studio
- ارجاع به Aspose.Slides for .NET در پروژه شما

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="ساخته شده با Aspose.Slides" title="مشاهده آنلاین فایل‌های POTX" description="برنامه رایگان Aspose.Slides Viewer با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های POTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Viewer" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides فایل‌های شما را چگونه نمایش می‌دهد.
- فایل POTX خود را بارگذاری کنید و اسلایدهای آن را فوراً ببینید.
- روی رایانه و موبایل کار می‌کند، بدون نیاز به PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" %}}

فایل‌هایی با پسوند .POTX قالب‌های ارائه Microsoft PowerPoint در قالب Open XML هستند. برخلاف قالب دودویی POT، قالب POTX بر پایه استاندارد Office Open XML است. فایل‌های POTX چیدمان اسلایدها، تم‌ها، سبک‌ها، پس‌زمینه‌ها، طرح‌های رنگی، فونت‌ها و دیگر قالب‌بندی‌های قابل استفاده مجدد را برای ساخت ارائه‌های جدید ذخیره می‌کنند.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="مشاهده فایل‌های دیگر" subTitle="می‌توانید ارائه‌ها را در قالب‌های دیگر نیز باز کرده و مشاهده کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/odp/" name="ODP" description="ارائه OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/otp/" name="OTP" description="قالب ارائه OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pot/" name="POT" description="قالب PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/potm/" name="POTM" description="قالب PowerPoint با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pps/" name="PPS" description="نمایش اسلاید PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/ppsm/" name="PPSM" description="نمایش اسلاید PowerPoint با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/ppsx/" name="PPSX" description="نمایش اسلاید PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/ppt/" name="PPT" description="ارائه PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pptm/" name="PPTM" description="ارائه PowerPoint با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pptx/" name="PPTX" description="ارائه PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
