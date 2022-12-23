---
title: تحرير PPT في جافا
url: /ar/java/editor/ppt/
keywords: تحرير PPT ، تحرير PowerPoint ، PPT ، PowerPoint ، Java API ، مكتبة Java
description: تحرير PPT في جافا. استخدم Java Library API لتحرير عرض PowerPoint التقديمي
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحرير PPT في جافا" h2="مكتبة Java عالية السرعة ومتعددة المنصات لتحرير PPT باستخدام كود Java" >}}

{{% blocks/products/pf/feature-page-section h2="تحرير PPT باستخدام Aspose.Slides" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) هي مكتبة Java قوية تُستخدم لمعالجة العروض التقديمية وتحريرها. يمكنك تحرير عرض PPT عن طريق إضافة سطر جديد من النص إليه. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="تحرير PPT في جافا" %}}
باستخدام [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) ، يمكنك إضافة سطر جديد من النص إلى مستند PPT ببضعة سطور من التعليمات البرمجية.

{{% blocks/products/pf/agp/code-block title="كود جافا لتحرير PPT" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحرير PPT في Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت ** Aspose.Slides for Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف المكتبة كمرجع في مشروعك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل العرض التقديمي PPT الذي تريد تحريره.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف سطرًا جديدًا من النص.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ ملف PowerPoint الذي تم تغييره.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="قم بتحرير الملفات الأخرى" subTitle="يمكنك أيضًا تحرير الملفات بتنسيقات أخرى" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}