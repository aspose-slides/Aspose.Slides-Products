---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تنقيح النص في عروض ODP التقديمية باستخدام Python
url: /ar/python-net/redaction/odp/
description: ابحث عن النص الحساس واستبدله في عروض ODP التقديمية باستخدام Python.
keywords: تنقيح ODP، البحث عن النص واستبداله في ODP، تحديث عرض ODP التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تنقيح النص في عروض ODP التقديمية باستخدام Python" h2="أنشئ تطبيقات Python تبحث عن النص الحساس وتستبدله في العروض التقديمية باستخدام Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تنقيح النص في عرض ODP تقديمي باستخدام Python" variant="code" %}}

باستخدام [Aspose.Slides for Python via .NET](/slides/ar/python-net/)، يمكنك استبدال النص الحساس في عرض ODP التقديمي بالكامل. استخدم `Presentation.replace_text` مع `TextSearchOptions` للتحكم في البحث، ثم احفظ العرض التقديمي المعدَّل.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تنقيح النص في عرض ODP تقديمي – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.odp") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تنقيح النص في عرض ODP تقديمي باستخدام Python" intro="اتبع هذه الخطوات لاستبدال النص الحساس في عرض ODP تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف ODP باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) مع `TextSearchOptions` لاستبدال النص المطلوب.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي المعدَّل باستخدام `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="مبني باستخدام Aspose.Slides" title="تنقيح ملفات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Redaction المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Redaction" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يبحث Aspose.Slides عن النص ويستبدله قبل أن تكتب الكود.
- ابحث عن النص واستبدله في ملف ODP، بما في ذلك باستخدام التعبيرات النمطية.
- نزّل الملف المنقَّح.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتنقيح" subTitle="استخدم Python لتنقيح النص في تنسيقات العروض التقديمية المدعومة الأخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
