---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: إزالة التعليقات التوضيحية من PPTX باستخدام .NET
url: /ar/net/annotation/pptx/ 
description: أزل التعليقات ومؤلفي التعليقات من عروض PPTX التقديمية باستخدام C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إزالة التعليقات ومؤلفي التعليقات من PPTX باستخدام C#" h2="أنشئ تطبيقات .NET تدير التعليقات ومؤلفيها في ملفات العروض التقديمية باستخدام واجهات API من جانب الخادم." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إزالة التعليقات من PPTX عبر C#" variant="code" %}}

استخدم [Aspose.Slides for .NET](/slides/ar/net/) لإزالة التعليقات ومؤلفي التعليقات من ملفات العروض التقديمية بتنسيق PPTX. يفرّغ المثال أدناه مجموعة `Comments` لكل مؤلف، ثم يفرّغ مجموعة `CommentAuthors` في العرض التقديمي.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف التعليقات التوضيحية من PPTX – C#" >}}
```cs
using var presentation = new Presentation("example.pptx");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إزالة التعليقات من PPTX عبر C#" intro="اتبع هذه الخطوات لإزالة التعليقات ومؤلفي التعليقات من عرض تقديمي بتنسيق PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ثبّت Aspose.Slides for .NET. راجع [التثبيت](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPTX باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}كرّر عبر مجموعة `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فرّغ مجموعة `Comments` لكل مؤلف تعليقات.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فرّغ مجموعة `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي المحدّث باستخدام `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="مبني باستخدام Aspose.Slides" title="إزالة تعليقات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Annotation المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Annotation" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يزيل Aspose.Slides التعليقات قبل أن تكتب الشيفرة.
- أزل جميع التعليقات من ملف PPTX.
- نزّل الملف المنظَّف.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتعليقات التوضيحية" subTitle="باستخدام C#، يمكنك أيضًا إزالة التعليقات التوضيحية من تنسيقات أخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
