---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: إزالة التعليقات من PPTX باستخدام Python
url: /ar/python-net/annotation/pptx/ 
description: أزل التعليقات ومؤلفي التعليقات من عروض PPTX التقديمية في Python باستخدام Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إزالة التعليقات ومؤلفي التعليقات من PPTX باستخدام Python" h2="استخدم Aspose.Slides for Python via .NET لإزالة تعليقات العرض التقديمي ومؤلفيها." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إزالة التعليقات من PPTX عبر Python" variant="code" %}}

يوفّر [Aspose.Slides for Python via .NET](/slides/ar/python-net/) الوصول إلى التعليقات ومؤلفي التعليقات المخزّنة في عرض تقديمي بتنسيق PPTX. حمّل الملف باستخدام `Presentation`، وفرّغ مجموعة `comments` لكل مؤلف، وفرّغ `comment_authors`، ثم احفظ النتيجة بتنسيق PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="إزالة التعليقات من PPTX باستخدام Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إزالة التعليقات من PPTX عبر Python" intro="اتبع هذه الخطوات لإزالة جميع التعليقات ومؤلفي التعليقات من عرض تقديمي بتنسيق PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ثبّت [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف PPTX باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}كرّر عبر `comment_authors` وفرّغ مجموعة `comments` لكل مؤلف.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فرّغ مجموعة `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ `save` مع `SaveFormat.PPTX` لكتابة عرض PPTX التقديمي المحدّث.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="مبني باستخدام Aspose.Slides" title="إزالة تعليقات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Annotation المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Annotation" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يزيل Aspose.Slides التعليقات قبل أن تكتب الشيفرة.
- أزل جميع التعليقات من ملف PPTX.
- نزّل الملف المنظَّف.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتعليقات التوضيحية" subTitle="باستخدام Python، يمكنك أيضًا إزالة التعليقات التوضيحية من تنسيقات أخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
