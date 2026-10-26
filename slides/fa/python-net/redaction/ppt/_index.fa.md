---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: پنهان‌سازی متن در ارائه‌های PPT با Python
url: /fa/python-net/redaction/ppt/
description: متن حساس را در ارائه‌های PPT با Python پیدا و جایگزین کنید.
keywords: پنهان‌سازی اطلاعات PPT، یافتن و جایگزینی متن در PPT، به‌روزرسانی ارائه PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="پنهان‌سازی متن در ارائه‌های PPT با Python" h2="برنامه‌های Python بسازید که با Aspose.Slides متن حساس را در ارائه‌ها پیدا و جایگزین می‌کنند." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="پنهان‌سازی متن در یک ارائه PPT با Python" variant="code" %}}

با [Aspose.Slides for Python via .NET](/slides/fa/python-net/) می‌توانید متن حساس را در سراسر یک ارائه PPT جایگزین کنید. از `Presentation.replace_text` همراه با `TextSearchOptions` برای کنترل جستجو استفاده کنید و سپس ارائه تغییریافته را ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="پنهان‌سازی متن در یک ارائه PPT – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه پنهان‌سازی متن در یک ارائه PPT با Python" intro="برای جایگزینی متن حساس در یک ارائه PPT این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) همراه با `TextSearchOptions` برای جایگزینی متن موردنظر استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه تغییریافته را با `SaveFormat.PPT` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="ساخته شده با Aspose.Slides" title="پنهان‌سازی آنلاین اطلاعات در فایل‌های PPT" description="برنامه رایگان Aspose.Slides Redaction با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Redaction" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا و جایگزین می‌کند.
- متن را در فایل PPT خود پیدا و جایگزین کنید، حتی با عبارات باقاعده.
- فایل پردازش‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای پنهان‌سازی اطلاعات" subTitle="از Python برای پنهان‌سازی متن در سایر فرمت‌های ارائه پشتیبانی‌شده استفاده کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
