---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تنقيح ملفات عروض ODP التقديمية باستخدام Java
url: /ar/java/redaction/odp/
description: ابحث عن النص واستبدله في عروض ODP التقديمية بلغة Java باستخدام Aspose.Slides for Java.
keywords: تنقيح ODP، البحث عن النص واستبداله في ODP، تحديث عرض ODP التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تنقيح ODP باستخدام Java" h2="أنشئ تطبيقات Java تبحث عن النص وتستبدله في ملفات العروض التقديمية باستخدام واجهات API من جانب الخادم." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تنقيح عرض ODP تقديمي عبر Java" variant="code" %}}

باستخدام [Aspose.Slides for Java](/slides/ar/java/)، يمكنك البحث عن النص واستبداله في عروض ODP التقديمية. استخدم الأسلوب `SlideUtil.findAndReplaceText` للبحث في العرض التقديمي واستبدال النص المطابق بقيمة جديدة.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تنقيح عرض ODP تقديمي باستخدام Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تنقيح ODP عبر Java" intro="اتبع هذه الخطوات لتنقيح عرض ODP تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف ODP باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `SlideUtil.findAndReplaceText` للبحث عن النص واستبداله.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي المحدَّث باستخدام `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="مبني باستخدام Aspose.Slides" title="تنقيح ملفات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Redaction المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Redaction" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يبحث Aspose.Slides عن النص ويستبدله قبل أن تكتب الكود.
- ابحث عن النص واستبدله في ملف ODP، بما في ذلك باستخدام التعبيرات النمطية.
- نزّل الملف المنقَّح.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتنقيح" subTitle="باستخدام Java، يمكنك أيضًا تنقيح التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
