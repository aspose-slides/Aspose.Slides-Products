---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: پنهان‌سازی اطلاعات در فایل‌های ارائه ODP با استفاده از .NET
url: /fa/net/redaction/odp/
description: کد منبع C# برای یافتن و جایگزینی متن در ارائه‌های ODP.
keywords: پنهان‌سازی اطلاعات ODP، یافتن و جایگزینی متن در ODP، به‌روزرسانی ارائه ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="پنهان‌سازی اطلاعات در فایل‌های ODP با استفاده از C#" h2="برنامه‌های .NET بسازید که با APIهای سمت سرور متن را در ارائه‌ها پیدا و جایگزین می‌کنند." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="پنهان‌سازی اطلاعات در یک ارائه ODP با استفاده از C#" variant="code" %}}

با [Aspose.Slides for .NET](/slides/fa/net/) می‌توانید متن را در یک ارائه ODP پیدا و جایگزین کنید. از `Presentation.ReplaceText` همراه با `TextSearchOptions` برای کنترل جستجو استفاده کنید و سپس ارائه تغییریافته را ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="پنهان‌سازی اطلاعات در یک ارائه ODP با استفاده از C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه پنهان‌سازی اطلاعات در یک ارائه ODP با استفاده از C#" intro="برای جایگزینی متن در یک ارائه ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) همراه با `TextSearchOptions` برای جایگزینی متن موردنظر استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه تغییریافته را با `SaveFormat.Odp` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="ساخته شده با Aspose.Slides" title="پنهان‌سازی آنلاین اطلاعات در فایل‌های ODP" description="برنامه رایگان Aspose.Slides Redaction با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Redaction" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا و جایگزین می‌کند.
- متن را در فایل ODP خود پیدا و جایگزین کنید، حتی با عبارات باقاعده.
- فایل پردازش‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای پنهان‌سازی اطلاعات" subTitle="با C# می‌توانید اطلاعات را در فرمت‌های زیر نیز پنهان کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
