---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: إضافة علامة مائية إلى عروض ODP التقديمية باستخدام C#
url: /ar/net/watermark/odp/
description: أضف علامات مائية نصية ومصورة إلى عروض ODP التقديمية في C# باستخدام Aspose.Slides for .NET.
keywords: إضافة علامة مائية إلى ODP، إضافة علامة مائية نصية إلى ODP، إضافة علامة مائية مصورة إلى ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إضافة علامة مائية إلى عرض ODP تقديمي باستخدام C#" h2="أنشئ تطبيقات .NET تُدرج علامات مائية نصية أو مصورة في ملفات العروض التقديمية." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إضافة علامة مائية إلى عرض ODP تقديمي عبر C#" variant="code" %}}

باستخدام [Aspose.Slides for .NET](/slides/ar/net/) يمكنك إضافة علامات مائية نصية ومصورة إلى عروض ODP التقديمية. أضف شكل العلامة المائية إلى شريحة رئيسية لتظهر العلامة المائية على الشرائح التي تستخدم تلك الشريحة الرئيسية.

{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة علامة مائية نصية إلى ODP باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة علامة مائية مصورة إلى عرض ODP تقديمي باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إضافة علامة مائية إلى ODP باستخدام C#" intro="اتبع هذه الخطوات لإضافة علامة مائية نصية أو مصورة إلى ملفات ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف `ODP` باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اختر شريحة رئيسية من المجموعة `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `AddAutoShape` لإضافة شكل العلامة المائية.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `AddTextFrame` لإضافة نص العلامة المائية أو استخدم `AddImage` لعلامة مائية مصورة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف بالعلامة المائية باستخدام `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="مبني باستخدام Aspose.Slides" title="أضف علامات مائية إلى ملفات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Watermark المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Watermark" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يضيف Aspose.Slides العلامات المائية قبل كتابة الكود.
- أضف علامة مائية نصية أو مصورة إلى ملف ODP.
- نزّل الملف بالعلامة المائية.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى تدعم العلامات المائية" subTitle="باستخدام C# يمكنك أيضًا إضافة علامات مائية إلى التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
