---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: پنهان‌سازی اطلاعات در ارائه‌های PPTX با استفاده از C++
url: /fa/cpp/redaction/pptx/
description: اطلاعات را در ارائه‌های PPTX با C++ پنهان کنید. از Aspose.Slides for C++ برای یافتن و جایگزینی متن حساس در فایل‌های ارائه استفاده کنید.
keywords: پنهان‌سازی اطلاعات PPTX، یافتن و جایگزینی متن در PPTX، به‌روزرسانی ارائه PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="پنهان‌سازی اطلاعات در PPTX با استفاده از C++" h2="از Aspose.Slides for C++ برای یافتن و جایگزینی متن حساس در فایل‌های ارائه بدون Microsoft PowerPoint استفاده کنید." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="پنهان‌سازی اطلاعات در یک ارائه PPTX از طریق C++" variant="code" %}}

Aspose.Slides for C++ به شما امکان می‌دهد با جایگزینی متن حساس در اسلایدها، اطلاعات را در ارائه‌های PPTX پنهان کنید. از `SlideUtil::FindAndReplaceText` همراه با یک شیء `Presentation` برای جستجو در ارائه و جایگزینی متن مطابق پیش از ذخیره فایل به‌روزشده استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="پنهان‌سازی اطلاعات در یک ارائه PPTX با استفاده از C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه پنهان‌سازی اطلاعات در PPTX از طریق C++" intro="برای پنهان‌سازی اطلاعات در یک ارائه PPTX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از متد [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) برای یافتن و جایگزینی متن حساس استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل پردازش‌شده را با `SaveFormat::Pptx` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="ساخته شده با Aspose.Slides" title="پنهان‌سازی آنلاین اطلاعات در فایل‌های PPTX" description="برنامه رایگان Aspose.Slides Redaction با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Redaction" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا و جایگزین می‌کند.
- متن را در فایل PPTX خود پیدا و جایگزین کنید، حتی با عبارات باقاعده.
- فایل پردازش‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای پنهان‌سازی اطلاعات" subTitle="با C++ می‌توانید اطلاعات را در فرمت‌های زیر نیز پنهان کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
