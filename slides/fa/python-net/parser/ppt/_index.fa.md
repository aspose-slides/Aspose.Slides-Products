---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: استخراج متن از فایل‌های PPT با Python
url: /fa/python-net/parser/ppt/
description: متن و جزئیات قالب‌بندی متن را با Python از ارائه‌های PPT استخراج کنید.
keywords: تجزیه PPT با Python، تجزیه‌گر PPT Python، استخراج داده از PPT در Python، استخراج متن از PPT با Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="استخراج متن از ارائه‌های PPT با Python" h2="برنامه‌های Python بسازید که با Aspose.Slides متن و جزئیات قالب‌بندی را از ارائه‌های PowerPoint استخراج می‌کنند." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="استخراج متن از یک ارائه PPT با Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/fa/python-net/) متد ایستای [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) را در `SlideUtil` ارائه می‌کند. این متد اشیای `TextFrame` کل ارائه را برمی‌گرداند و می‌تواند متن اسلایدهای اصلی را نیز شامل شود. مثال زیر متن و جزئیات قلم مرتبط را از یک ارائه PPT استخراج می‌کند.

{{< blocks/products/pf/slides-design-update-10-2026/code title="استخراج متن از یک ارائه PPT – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه استخراج متن از PPT با Python" intro="برای استخراج متن از یک فایل PPT این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.get_all_text_frames` را فراخوانی کنید و مشخص کنید اسلایدهای اصلی شامل شوند یا نه.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی اشیای `TextFrame` برگشتی پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی مجموعه `paragraphs` هر قاب متن پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی مجموعه `portions` هر پاراگراف پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`text` و ویژگی‌های قالب‌بندی بخش فعلی را بخوانید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="ساخته شده با Aspose.Slides" title="استخراج آنلاین متن و تصاویر" description="برنامه رایگان Aspose.Slides Parser با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Parser" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides فایل‌های شما را چگونه می‌خواند.
- یک فایل PPT بارگذاری کنید و متن و تصاویر آن را دریافت کنید.
- همه را در یک بایگانی ZIP دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای تجزیه" subTitle="با Python می‌توانید متن را از سایر قالب‌های ارائه پشتیبانی‌شده نیز استخراج کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
