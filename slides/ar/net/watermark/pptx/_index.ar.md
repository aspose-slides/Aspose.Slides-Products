---
title: أضف علامة مائية إلى PPTX ملفات العروض التقديمية باستخدام .NET
url: /ar/net/watermark/pptx/
keywords: إضافة علامة مائية PPTX ، إضافة علامة مائية نصية PPTX ، إضافة علامة مائية للصورة PPTX
description: C# شفرة المصدر لإضافة العلامة المائية إلى العرض التقديمي PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="أضف علامة مائية إلى العرض التقديمي PPTX باستخدام C#" h2="أنشئ تطبيقاتك الخاصة بـ .NET لإدراج نص أو علامة مائية للصورة في عرض PPT أو PPTX أو ODP باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="أضف علامة مائية إلى العرض التقديمي PPTX عبر C#" %}}
باستخدام Aspose.Slides for .NET ، يمكنك إضافة علامة مائية إلى العرض التقديمي PPTX. تعتبر العلامات المائية جزءًا أساسيًا من أي عرض تقديمي. يتم استخدامها لحماية محتوى العرض التقديمي من النسخ أو الاستخدام دون إذن. العلامة المائية هي صورة أو نص مرئي أو غير مرئي يتم وضعه أعلى العرض التقديمي. يمكن استخدامه لتحديد مالك العرض ولمنع الاستخدام غير المصرح به. يمكن أيضًا استخدام العلامات المائية لإضافة لمسة احترافية إلى العرض التقديمي ولجعله يبدو أكثر صقلًا. 
{{% blocks/products/pf/agp/code-block title="أضف علامة مائية نصية إلى PPTX باستخدام C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="أضف علامة مائية للصورة إلى العرض التقديمي PPTX باستخدام C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إضافة علامة مائية إلى PPTX عبر C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لإضافة علامة مائية نصية إلى ملفات PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPTX بمثيل عرض تقديمي
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
احفظ النتيجة بتنسيق PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="التنسيقات الأخرى المدعومة" subTitle="باستخدام C# ، يمكنك أيضًا إضافة علامة مائية إلى التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}