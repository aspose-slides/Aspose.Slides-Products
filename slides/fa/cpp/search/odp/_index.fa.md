---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: جستجوی متن در ارائه‌های ODP با استفاده از C++
url: /fa/cpp/search/odp/
description: متن را در ارائه‌های ODP با C++ جستجو کنید. از Aspose.Slides for C++ برای یافتن متن در فایل‌های ارائه استفاده کنید.
keywords: جستجوی کلمات در ODP، یافتن متن در ODP، جستجو در متن ارائه ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="جستجوی متن در ODP با استفاده از C++" h2="از Aspose.Slides for C++ برای یافتن متن در فایل‌های ارائه بدون Microsoft PowerPoint استفاده کنید." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="جستجوی متن در یک ارائه ODP از طریق C++" variant="code" %}}

Aspose.Slides for C++ به شما امکان می‌دهد متن را در ارائه‌های ODP جستجو کنید. از `SlideUtil::GetAllTextBoxes` برای جمع‌آوری قاب‌های متنی یک اسلاید استفاده کنید و سپس بررسی کنید که متن آن‌ها شامل عبارت موردنظر باشد.

{{< blocks/products/pf/slides-design-update-10-2026/code title="جستجوی متن در یک ارائه ODP با استفاده از C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه جستجوی متن در ODP از طریق C++" intro="برای جستجوی متن در یک ارائه ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اسلاید موردنظر را با `Presentation::get_Slides` و قاب‌های متنی آن را با [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) دریافت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}بررسی کنید که متن هر قاب شامل عبارت موردنظر باشد.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="ساخته شده با Aspose.Slides" title="جستجوی آنلاین متن در فایل‌های ODP" description="برنامه رایگان Aspose.Slides Search با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Search" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا می‌کند.
- در فایل ODP خود متن ساده یا عبارات باقاعده را جستجو کنید.
- نتایج را به‌صورت فایل متنی دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای جستجو" subTitle="با C++ می‌توانید در فرمت‌های زیر نیز متن را جستجو کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
