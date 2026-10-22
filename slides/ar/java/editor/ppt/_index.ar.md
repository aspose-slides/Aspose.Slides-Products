---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحرير PPT في جافا
url: /ar/java/editor/ppt/
keywords: تحرير PPT ، تحرير PowerPoint ، PPT ، PowerPoint ، Java API ، مكتبة Java
description: تحرير PPT في جافا. استخدم Java Library API لتحرير عرض PowerPoint التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحرير PPT في جافا" h2="مكتبة Java عالية السرعة ومتعددة المنصات لتحرير PPT باستخدام كود Java" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحرير PPT في جافا" variant="code" %}}

باستخدام [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) ، يمكنك إضافة سطر جديد من النص إلى مستند PPT ببضعة سطور من التعليمات البرمجية.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود جافا لتحرير PPT" >}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحرير PPT باستخدام Aspose.Slides" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) هي مكتبة Java قوية تُستخدم لمعالجة العروض التقديمية وتحريرها. يمكنك تحرير عرض PPT عن طريق إضافة سطر جديد من النص إليه.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحرير PPT في Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت ** Aspose.Slides for Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل العرض التقديمي PPT الذي تريد تحريره.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف سطرًا جديدًا من النص.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ ملف PowerPoint الذي تم تغييره.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="قم بتحرير الملفات الأخرى" subTitle="يمكنك أيضًا تحرير الملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
