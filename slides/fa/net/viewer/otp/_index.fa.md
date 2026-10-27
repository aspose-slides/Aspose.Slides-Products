---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: مشاهده OTP در C#
keywords: مشاهده OTP, باز کردن OTP, نمایشگر OTP, OTP, C# API, کتابخانه .NET
weight: 6830
url: /fa/net/viewer/otp/ 
description: فایل‌های OTP را در C# مشاهده کنید. با Aspose.Slides for .NET فایل‌های ارائه را باز کنید و به‌صورت HTML ذخیره کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="مشاهده OTP در C#" h2="API زبان C# برای باز کردن فایل‌های OTP و ذخیره آن‌ها به‌صورت HTML واکنش‌گرا."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="مشاهده OTP با Aspose.Slides" %}}

برای مشاهده فایل‌های OTP از API [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) استفاده کنید؛ یک API قدرتمند، کامل و آسان برای C#. مدیر بسته [NuGet](https://www.nuget.org/packages/aspose.slides.net) را باز کنید، **Aspose.Slides** را جستجو و نصب کنید. همچنین می‌توانید دستور زیر را در Package Manager Console اجرا کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="دستور Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

با [**Aspose.Slides for .NET**](/slides/fa/net/) می‌توانید یک فایل OTP را بارگذاری کرده و با چند خط کد به‌صورت HTML واکنش‌گرا ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد C# برای مشاهده OTP" >}}
```cs
using var presentation = new Presentation("presentation.otp");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه مشاهده OTP در C#" intro="Aspose.Slides به توسعه‌دهندگان امکان می‌دهد فایل‌های OTP را تنها با چند خط کد مشاهده کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** را نصب کنید. [**نصب**](https://docs.aspose.com/slides/net/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به‌عنوان مرجع به پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل `OTP` را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک شیء `ResponsiveHtmlController` برای خروجی HTML واکنش‌گرا ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک شیء `HtmlOptions` ایجاد کنید و ویژگی `HtmlFormatter` را تنظیم کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل OTP را با `SaveFormat.Html` به‌صورت HTML ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="پیش‌نیازهای سیستم" intro="Aspose.Slides for .NET از همه سیستم‌عامل‌های اصلی پشتیبانی می‌کند. مطمئن شوید پیش‌نیازهای زیر را دارید." %}}

- Microsoft Windows یا سیستم‌عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin
- یک محیط توسعه مانند Microsoft Visual Studio
- ارجاع به Aspose.Slides for .NET در پروژه شما

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="ساخته شده با Aspose.Slides" title="مشاهده آنلاین فایل‌های OTP" description="برنامه رایگان Aspose.Slides Viewer با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های OTP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Viewer" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides فایل‌های شما را چگونه نمایش می‌دهد.
- فایل OTP خود را بارگذاری کنید و اسلایدهای آن را فوراً ببینید.
- روی رایانه و موبایل کار می‌کند، بدون نیاز به PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

فایل‌هایی با پسوند `.OTP` قالب‌های ارائه OpenDocument هستند. این فایل‌ها چیدمان‌ها، سبک‌ها، قالب‌بندی، پس‌زمینه‌ها و دیگر محتوای قابل استفاده مجدد را برای ساخت ارائه‌های جدید با طراحی یکدست ذخیره می‌کنند. فایل‌های OTP را می‌توان با برنامه‌هایی که از OpenDocument Format (ODF) پشتیبانی می‌کنند ساخت و باز کرد. این قالب با قالب‌های الگوی Microsoft PowerPoint یعنی POT و POTX قابل مقایسه است.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="مشاهده فایل‌های دیگر" subTitle="می‌توانید ارائه‌ها را در قالب‌های دیگر نیز باز کرده و مشاهده کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/odp/" name="ODP" description="ارائه OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pot/" name="POT" description="قالب PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/potm/" name="POTM" description="قالب PowerPoint با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/potx/" name="POTX" description="قالب PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pps/" name="PPS" description="نمایش اسلاید PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/ppsm/" name="PPSM" description="نمایش اسلاید PowerPoint با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/ppsx/" name="PPSX" description="نمایش اسلاید PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/ppt/" name="PPT" description="ارائه PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pptm/" name="PPTM" description="ارائه PowerPoint با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/viewer/pptx/" name="PPTX" description="ارائه PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
