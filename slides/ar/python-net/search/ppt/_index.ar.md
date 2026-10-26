---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: البحث عن النص في عروض PPT التقديمية باستخدام Python
url: /ar/python-net/search/ppt/
description: ابحث عن النص في عروض PPT التقديمية باستخدام Python وAspose.Slides.
keywords: البحث عن النص في PPT، العثور على الكلمات في PPT، البحث في عرض PPT التقديمي باستخدام Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="البحث عن النص في عروض PPT التقديمية باستخدام Python" h2="أنشئ تطبيقات Python تعثر على النص في عروض PowerPoint التقديمية باستخدام Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="البحث عن النص في عرض PPT تقديمي باستخدام Python" variant="code" %}}

باستخدام [Aspose.Slides for Python via .NET](/slides/ar/python-net/)، يمكنك استخدام [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) للعثور في كل شريحة على إطارات النص التي تحتوي على سلسلة محددة.

{{< blocks/products/pf/slides-design-update-10-2026/code title="البحث عن النص في عرض PPT تقديمي – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية البحث عن النص في PPT باستخدام Python" intro="اتبع هذه الخطوات للبحث عن النص في عرض PPT تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف PPT باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على الشرائح واستدعِ [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) لكل منها.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اقرأ الخاصية `text` لكل إطار نص مطابق.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="مبني باستخدام Aspose.Slides" title="البحث عن النص في ملفات PPT عبر الإنترنت" description="تطبيق Aspose.Slides Search المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Search" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يعثر Aspose.Slides على النص قبل أن تكتب الكود.
- ابحث في ملف PPT عن نص عادي أو تعبيرات نمطية.
- نزّل النتائج كملف نصي.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للبحث" subTitle="استخدم Python للبحث عن النص في تنسيقات العروض التقديمية المدعومة الأخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
