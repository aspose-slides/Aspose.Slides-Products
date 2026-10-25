---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: إضافة علامة مائية إلى ملفات عروض PPTX التقديمية باستخدام Java
url: /ar/java/watermark/pptx/
description: أضف علامات مائية نصية ومصورة إلى عروض PPTX التقديمية في Java باستخدام Aspose.Slides for Java.
keywords: إضافة علامة مائية إلى PPTX، إضافة علامة مائية نصية إلى PPTX، إضافة علامة مائية مصورة إلى PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إضافة علامة مائية إلى عرض PPTX تقديمي باستخدام Java" h2="أنشئ تطبيقات Java تُدرج علامات مائية نصية أو مصورة في ملفات العروض التقديمية باستخدام واجهات برمجية على الخادم." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إضافة علامة مائية إلى عرض PPTX تقديمي عبر Java" variant="code" %}}

باستخدام [Aspose.Slides for Java](/slides/ar/java/) يمكنك إضافة علامات مائية نصية ومصورة إلى عروض PPTX التقديمية. أضف شكل العلامة المائية إلى شريحة رئيسية لتظهر العلامة المائية على الشرائح التي تستخدم تلك الشريحة الرئيسية.

{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة علامة مائية نصية إلى PPTX باستخدام Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة علامة مائية مصورة إلى عرض PPTX تقديمي باستخدام Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إضافة علامة مائية إلى PPTX باستخدام Java" intro="اتبع هذه الخطوات لإضافة علامة مائية نصية أو مصورة إلى ملفات PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف `PPTX` باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اختر شريحة رئيسية باستخدام الأسلوب `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `addAutoShape` لإضافة شكل العلامة المائية.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `addTextFrame` لإضافة نص العلامة المائية أو استخدم `addImage` لعلامة مائية مصورة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي بالعلامة المائية بتنسيق PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="مبني باستخدام Aspose.Slides" title="أضف علامات مائية إلى ملفات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Watermark المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Watermark" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يضيف Aspose.Slides العلامات المائية قبل كتابة الكود.
- أضف علامة مائية نصية أو مصورة إلى ملف PPTX.
- نزّل الملف بالعلامة المائية.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى تدعم العلامات المائية" subTitle="باستخدام Java يمكنك أيضًا إضافة علامات مائية إلى التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
