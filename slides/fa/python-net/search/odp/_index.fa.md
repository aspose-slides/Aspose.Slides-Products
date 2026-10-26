---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: جستجوی متن در ارائه‌های ODP با Python
url: /fa/python-net/search/odp/
description: متن را در ارائه‌های ODP با Python و Aspose.Slides جستجو کنید.
keywords: جستجوی متن در ODP، یافتن کلمات در ODP، جستجو در ارائه ODP با Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="جستجوی متن در ارائه‌های ODP با Python" h2="برنامه‌های Python بسازید که با Aspose.Slides متن را در ارائه‌های OpenDocument پیدا می‌کنند." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="جستجوی متن در یک ارائه ODP با Python" variant="code" %}}

با [Aspose.Slides for Python via .NET](/slides/fa/python-net/) می‌توانید از [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) برای یافتن قاب‌های متنی هر اسلاید که شامل یک رشته مشخص هستند استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="جستجوی متن در یک ارائه ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه جستجوی متن در ODP با Python" intro="برای جستجوی متن در یک ارائه ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اسلایدها را پیمایش کنید و برای هر کدام [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ویژگی `text` هر قاب متنی مطابق را بخوانید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="ساخته شده با Aspose.Slides" title="جستجوی آنلاین متن در فایل‌های ODP" description="برنامه رایگان Aspose.Slides Search با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Search" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا می‌کند.
- در فایل ODP خود متن ساده یا عبارات باقاعده را جستجو کنید.
- نتایج را به‌صورت فایل متنی دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای جستجو" subTitle="از Python برای جستجوی متن در سایر فرمت‌های ارائه پشتیبانی‌شده استفاده کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
