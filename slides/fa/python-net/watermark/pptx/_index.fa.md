---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: افزودن واترمارک به ارائه‌های PPTX با Python
url: /fa/python-net/watermark/pptx/
description: با Python و Aspose.Slides واترمارک متنی و تصویری به ارائه‌های PPTX اضافه کنید.
keywords: افزودن واترمارک به PPTX، افزودن واترمارک متنی به PPTX، افزودن واترمارک تصویری به PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="افزودن واترمارک به ارائه‌های PPTX با Python" h2="برنامه‌های Python بسازید که با Aspose.Slides واترمارک متنی یا تصویری به ارائه‌های PPTX اضافه می‌کنند." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="افزودن واترمارک به یک ارائه PPTX با Python" variant="code" %}}

با [Aspose.Slides for Python via .NET](/slides/fa/python-net/) می‌توانید بدون Microsoft PowerPoint یک واترمارک متنی یا تصویری به ارائه PPTX اضافه کنید. واترمارک می‌تواند مالکیت را نشان دهد، ارائه را محرمانه یا پیش‌نویس علامت‌گذاری کند یا هویت برند یکپارچه‌ای ایجاد کند. نمونه‌های زیر واترمارک را روی نخستین اسلاید اصلی قرار می‌دهند تا در اسلایدهایی که از آن استفاده می‌کنند نمایش داده شود.

{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک متنی به ارائه PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک تصویری به ارائه PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه افزودن واترمارک به PPTX با Python" intro="برای افزودن واترمارک متنی به ارائه PPTX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نخستین اسلاید اصلی را از مجموعه `masters` دریافت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`add_auto_shape` را برای افزودن یک مستطیل به اسلاید اصلی فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`add_text_frame` را برای افزودن متن واترمارک فراخوانی کنید، سپس شکل را قالب‌بندی و قفل کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`save` را با `SaveFormat.PPTX` فراخوانی کنید تا ارائه دارای واترمارک ذخیره شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="ساخته شده با Aspose.Slides" title="افزودن آنلاین واترمارک به فایل‌های PPTX" description="برنامه رایگان Aspose.Slides Watermark با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Watermark" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه واترمارک اضافه می‌کند.
- یک واترمارک متنی یا تصویری به فایل PPTX خود اضافه کنید.
- فایل دارای واترمارک را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌کننده واترمارک" subTitle="با Python می‌توانید به سایر قالب‌های ارائه پشتیبانی‌شده نیز واترمارک اضافه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
