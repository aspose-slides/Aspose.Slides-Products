---
title: أضف علامة مائية إلى ODP ملفات العروض التقديمية باستخدام Java
url: /ar/java/watermark/odp/
keywords: إضافة علامة مائية ODP ، إضافة علامة مائية نصية ODP ، إضافة علامة مائية للصورة ODP
description: Java شفرة المصدر لإضافة العلامة المائية إلى العرض التقديمي ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="أضف علامة مائية إلى العرض التقديمي ODP باستخدام Java" h2="أنشئ تطبيقاتك الخاصة بـ Java لإدراج نص أو علامة مائية للصورة في عرض PPT أو PPTX أو ODP باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="أضف علامة مائية إلى العرض التقديمي ODP عبر Java" %}}
باستخدام Aspose.Slides for Java ، يمكنك إضافة علامة مائية إلى العرض التقديمي ODP. تعتبر العلامات المائية جزءًا أساسيًا من أي عرض تقديمي. يتم استخدامها لحماية محتوى العرض التقديمي من النسخ أو الاستخدام دون إذن. العلامة المائية هي صورة أو نص مرئي أو غير مرئي يتم وضعه أعلى العرض التقديمي. يمكن استخدامه لتحديد مالك العرض ولمنع الاستخدام غير المصرح به. يمكن أيضًا استخدام العلامات المائية لإضافة لمسة احترافية إلى العرض التقديمي ولجعله يبدو أكثر صقلًا. 
{{% blocks/products/pf/agp/code-block title="أضف علامة مائية نصية إلى ODP باستخدام Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="أضف علامة مائية للصورة إلى العرض التقديمي ODP باستخدام Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إضافة علامة مائية إلى ODP عبر Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لإضافة علامة مائية نصية إلى ملفات ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل ODP بمثيل عرض تقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حدد العرض التقديمي الرئيسي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف نوع الشكل باستخدام أسلوب AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف نص العلامة المائية باستخدام طريقة AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="التنسيقات الأخرى المدعومة" subTitle="باستخدام Java ، يمكنك أيضًا إضافة علامة مائية إلى التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}