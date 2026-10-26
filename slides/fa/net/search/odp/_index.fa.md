---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: جستجوی متن در فایل‌های ارائه ODP با استفاده از .NET
url: /fa/net/search/odp/
description: کد منبع C# برای جستجوی متن در ارائه‌های ODP.
keywords: جستجوی متن در ODP، یافتن متن در ODP، جستجو در متن ارائه ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="جستجوی متن در فایل‌های ODP با استفاده از C#" h2="برنامه‌های .NET بسازید که با APIهای سمت سرور متن را در ارائه‌ها پیدا می‌کنند." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="جستجوی متن در یک ارائه ODP با استفاده از C#" variant="code" %}}

با [Aspose.Slides for .NET](/slides/fa/net/) می‌توانید متن را در یک ارائه ODP جستجو کنید. قاب‌های متنی یک اسلاید را با `SlideUtil.GetAllTextBoxes` دریافت کنید و سپس مقادیر `Text` آن‌ها را برای عبارت موردنظر بررسی کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="جستجوی متن در یک ارائه ODP با استفاده از C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه جستجوی متن در یک ارائه ODP با استفاده از C#" intro="برای جستجوی متن در یک ارائه ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اسلاید موردنظر را از `Presentation.Slides` دریافت کنید و به یک متغیر اختصاص دهید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قاب‌های متنی آن را با [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) دریافت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}بررسی کنید که مقدار `Text` هر قاب شامل عبارت موردنظر باشد.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="ساخته شده با Aspose.Slides" title="جستجوی آنلاین متن در فایل‌های ODP" description="برنامه رایگان Aspose.Slides Search با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Search" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا می‌کند.
- در فایل ODP خود متن ساده یا عبارات باقاعده را جستجو کنید.
- نتایج را به‌صورت فایل متنی دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای جستجو" subTitle="با C# می‌توانید در فرمت‌های زیر نیز متن را جستجو کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
