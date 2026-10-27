---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: إزالة التعليقات التوضيحية من ODP باستخدام Java
url: /ar/java/annotation/odp/ 
description: أزل التعليقات ومؤلفي التعليقات من عروض ODP التقديمية في Java باستخدام Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إزالة التعليقات ومؤلفي التعليقات من ODP باستخدام Java" h2="استخدم Aspose.Slides for Java لإزالة التعليقات ومؤلفي التعليقات من ملفات العروض التقديمية." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إزالة التعليقات من ODP عبر Java" variant="code" %}}

يتيح لك Aspose.Slides for Java إزالة التعليقات ومؤلفي التعليقات من عروض ODP التقديمية. حمّل ملفًا باستخدام الفئة `Presentation`، وكرّر عبر كائنات `ICommentAuthor` من `getCommentAuthors`، وامسح تعليقاتها، ثم احفظ العرض التقديمي المحدّث.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف التعليقات التوضيحية من ODP – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إزالة التعليقات من ODP عبر Java" intro="اتبع هذه الخطوات لإزالة التعليقات ومؤلفي التعليقات من عرض تقديمي بتنسيق ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ثبّت Aspose.Slides for Java. راجع [التثبيت](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف ODP باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}كرّر عبر كائنات `ICommentAuthor` من `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}امسح تعليقات كل مؤلف باستخدام `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فرّغ مجموعة مؤلفي التعليقات واحفظ ملف ODP المحدّث.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="مبني باستخدام Aspose.Slides" title="إزالة تعليقات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Annotation المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Annotation" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يزيل Aspose.Slides التعليقات قبل أن تكتب الشيفرة.
- أزل جميع التعليقات من ملف ODP.
- نزّل الملف المنظَّف.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتعليقات التوضيحية" subTitle="باستخدام Java، يمكنك أيضًا إزالة التعليقات التوضيحية من تنسيقات أخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
