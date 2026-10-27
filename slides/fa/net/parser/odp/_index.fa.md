---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: استخراج متن از فایل‌های ODP با .NET
url: /fa/net/parser/odp/ 
description: کد منبع C# برای استخراج متن از فایل‌های ODP با .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تجزیه فایل‌های ODP با C#" h2="متن را استخراج کنید و قالب‌بندی متن را در فایل‌های ODP با APIهای سمت سرور .NET بررسی کنید."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تجزیه فایل ODP با C#" %}}

از [Aspose.Slides for .NET](/slides/fa/net/) برای استخراج متن از ارائه‌های ODP استفاده کنید. بسته را از [NuGet](https://www.nuget.org/packages/aspose.slides.net) نصب کنید یا دستور زیر را در Package Manager Console اجرا کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="دستور" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="تجزیه فایل‌های ODP – C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تجزیه فایل‌های ODP در C#" intro="تجزیه پایه اسناد با API [Aspose.Slides for .NET](/slides/fa/net/) تنها به چند خط کد نیاز دارد." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قاب‌های متن را با `SlideUtil.GetAllTextFrames` دریافت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی قاب‌های متن، پاراگراف‌ها و بخش‌های متن پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}در صورت نیاز ویژگی‌های `Text`، `FontHeight` و `LatinFont.FontName` را بخوانید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="پیش‌نیازهای سیستم" intro="یک محیط اجرای .NET پشتیبانی‌شده و ارجاع به بسته Aspose.Slides for .NET لازم است. می‌توانید از Visual Studio یا محیط توسعه C# سازگار دیگری استفاده کنید." %}}

- محیط سازگار با .NET Framework، .NET، Mono یا Xamarin
- یک محیط توسعه C# مانند Visual Studio
- Aspose.Slides for .NET نصب‌شده از NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="ساخته شده با Aspose.Slides" title="استخراج آنلاین متن و تصاویر" description="برنامه رایگان Aspose.Slides Parser با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Parser" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides فایل‌های شما را چگونه می‌خواند.
- یک فایل ODP بارگذاری کنید و متن و تصاویر آن را دریافت کنید.
- همه را در یک بایگانی ZIP دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

فایل‌های ODP از قالب OpenDocument Presentation استفاده می‌کنند. ارائه شامل اسلایدهایی با متن، تصویر، قالب‌بندی، پویانمایی و رسانه‌های دیگر است. برنامه‌هایی که از قالب OpenDocument پشتیبانی می‌کنند، مانند OpenOffice و StarOffice، می‌توانند فایل‌های ODP را باز کنند.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای تجزیه" subTitle="با C# می‌توانید قالب‌های زیر را نیز تجزیه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/parser/ppt/" name="PPT" description="ارائه PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/parser/pptx/" name="PPTX" description="ارائه PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
