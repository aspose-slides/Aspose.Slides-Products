---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: مشاهده یا ویرایش فراداده PPSX با Python
url: /fa/python-net/metadata/ppsx/
description: ویژگی‌های فراداده داخلی و سفارشی فایل‌های PPSX را با Python مشاهده و ویرایش کنید.
keywords: ویرایش فراداده PPSX، مشاهده فراداده PPSX، ویرایش ویژگی‌های PPSX، مشاهده ویژگی‌های PPSX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="مشاهده و ویرایش فراداده PPSX با Python" h2="برنامه‌های Python بسازید که با Aspose.Slides ویژگی‌های داخلی و سفارشی ارائه‌ها را می‌خوانند و تغییر می‌دهند." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="مشاهده و تغییر فراداده PPSX با Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/fa/python-net/) به شما امکان می‌دهد فراداده داخلی را بخوانید و به‌روز کنید و ویژگی‌های سفارشی سند را در ارائه‌های PPSX اضافه، به‌روز یا حذف کنید. از طریق `Presentation.document_properties` به شیء [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) دسترسی پیدا کنید، آن را تغییر دهید و ارائه را در قالب PPSX ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="به‌روزرسانی ویژگی‌های داخلی PPSX – Python" >}}
```python
with slides.Presentation("presentation.ppsx") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.ppsx", slides.export.SaveFormat.PPSX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن و حذف ویژگی‌های سفارشی PPSX – Python" >}}
```python
with slides.Presentation("presentation.ppsx") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.ppsx", slides.export.SaveFormat.PPSX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه ویرایش فراداده PPSX با Python" intro="برای ویرایش فراداده یک فایل PPSX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPSX را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از طریق `Presentation.document_properties` به شیء `IDocumentProperties` آن دسترسی پیدا کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ویژگی‌های داخلی را به‌روز کنید یا برای ویژگی‌های سفارشی از `set_custom_property_value` و `remove_custom_property` استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه را با `Presentation.save` و `SaveFormat.PPSX` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="ساخته شده با Aspose.Slides" title="مشاهده و ویرایش آنلاین فراداده PPSX" description="برنامه رایگان Aspose.Slides Metadata با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPSX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Metadata" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides ویژگی‌ها را چگونه می‌خواند و می‌نویسد.
- ویژگی‌های داخلی و سفارشی فایل PPSX خود را مشاهده و ویرایش کنید.
- فایل به‌روزشده را ذخیره و دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های فراداده پشتیبانی‌شده" subTitle="با Python می‌توانید فراداده سایر قالب‌های ارائه پشتیبانی‌شده را نیز مدیریت کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
