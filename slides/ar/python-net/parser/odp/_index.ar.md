---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: استخراج النص من ملفات ODP باستخدام Python
url: /ar/python-net/parser/odp/
description: استخرج النص وتفاصيل تنسيقه من عروض ODP التقديمية باستخدام Python.
keywords: تحليل ODP باستخدام Python، محلل ODP في Python، استخراج البيانات من ODP في Python، استخراج النص من ODP باستخدام Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="استخراج النص من عروض ODP التقديمية باستخدام Python" h2="أنشئ تطبيقات Python تستخرج النص وتفاصيل تنسيقه من عروض OpenDocument التقديمية باستخدام Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="استخراج النص من عرض ODP تقديمي باستخدام Python" variant="code" %}}

يوفر [**Aspose.Slides for Python via .NET**](/slides/ar/python-net/) الأسلوب الثابت [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) في `SlideUtil`. يُرجع هذا الأسلوب كائنات `TextFrame` من العرض التقديمي بأكمله ويمكنه تضمين النص من الشرائح الرئيسية. يستخرج المثال التالي النص وتفاصيل الخط المرتبطة به من عرض ODP تقديمي.

{{< blocks/products/pf/slides-design-update-10-2026/code title="استخراج النص من عرض ODP تقديمي – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية استخراج النص من ODP باستخدام Python" intro="اتبع هذه الخطوات لاستخراج النص من ملف ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف ODP باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ `SlideUtil.get_all_text_frames` وحدد ما إذا كان سيتم تضمين الشرائح الرئيسية.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على كائنات `TextFrame` المُرجعة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على مجموعة `paragraphs` لكل إطار نص.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على مجموعة `portions` لكل فقرة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اقرأ `text` وخصائص التنسيق للجزء الحالي.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="مبني باستخدام Aspose.Slides" title="استخراج النص والصور عبر الإنترنت" description="تطبيق Aspose.Slides Parser المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Parser" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يقرأ Aspose.Slides ملفاتك قبل كتابة الكود.
- ارفع ملف ODP واحصل على نصه وصوره.
- نزّل كل شيء في أرشيف ZIP واحد.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتحليل" subTitle="باستخدام Python يمكنك أيضًا استخراج النص من تنسيقات العروض التقديمية الأخرى المدعومة." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
