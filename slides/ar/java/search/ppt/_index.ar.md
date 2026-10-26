---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: البحث عن النص في ملفات عروض PPT التقديمية باستخدام Java
url: /ar/java/search/ppt/
description: ابحث عن النص في عروض PPT التقديمية بلغة Java باستخدام Aspose.Slides for Java.
keywords: البحث عن الكلمات في PPT، البحث عن النص في PPT، البحث في نص عرض PPT التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="البحث عن النص في PPT باستخدام Java" h2="أنشئ تطبيقات Java تبحث عن النص في ملفات العروض التقديمية باستخدام واجهات API من جانب الخادم." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="البحث عن النص في عرض PPT تقديمي عبر Java" variant="code" %}}

باستخدام [Aspose.Slides for Java](/slides/ar/java/)، يمكنك البحث عن النص في عروض PPT التقديمية. استخدم الأسلوب `SlideUtil.getAllTextBoxes` لجمع إطارات النص، ثم افحص الكائنات `ITextFrame` و`IParagraph` و`IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="البحث عن النص في عرض PPT تقديمي باستخدام Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية البحث عن النص في PPT عبر Java" intro="اتبع هذه الخطوات للبحث عن النص في عرض PPT تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPT باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `SlideUtil.getAllTextBoxes` لجمع إطارات النص من كل شريحة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افحص الكائنات `ITextFrame` و`IParagraph` و`IPortion` للعثور على النص المطابق.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="مبني باستخدام Aspose.Slides" title="البحث عن النص في ملفات PPT عبر الإنترنت" description="تطبيق Aspose.Slides Search المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Search" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يعثر Aspose.Slides على النص قبل أن تكتب الكود.
- ابحث في ملف PPT عن نص عادي أو تعبيرات نمطية.
- نزّل النتائج كملف نصي.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للبحث" subTitle="باستخدام Java، يمكنك أيضًا البحث عن النص في التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
