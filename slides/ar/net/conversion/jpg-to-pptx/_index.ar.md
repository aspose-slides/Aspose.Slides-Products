---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل JPG إلى PPTX في C#
url: /ar/net/conversion/jpg-to-pptx/
keywords: تحويل JPG إلى PPTX ، JPG إلى PPTX ، PowerPoint ، JPG ، PPTX ، C# API ، مكتبة .NET
description: تحويل JPG إلى PPTX في C#. استخدم .NET library API لتحويل صور JPG إلى PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل JPG إلى PPTX في C#" h2="واجهة برمجة تطبيقات .NET API قوية ومتعددة المنصات لتحويل JPG إلى PPTX باستخدام كود C# على NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل JPG إلى PPTX في C#" variant="code" %}}

باستخدام [** Aspose.Slides for .NET **](https://products.aspose.com/slides/ar/net/) ، يمكنك تحويل صورة JPG إلى عرض PowerPoint تقديمي ببضعة سطور من التعليمات البرمجية:

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود C# لتحويل JPG إلى PPTX" >}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل JPG إلى PPTX باستخدام Aspose.Slides" %}}

[** Aspose.Slides for .NET **](https://products.aspose.com/slides/ar/net/) هي مكتبة .NET قوية تُستخدم لإنشاء وتحويل ومعالجة عروض PowerPoint التقديمية وملفات PDF ومستندات HTML و وغيرها من الملفات. عندما تقوم بتحويل JPG إلى PPTX ، فأنت تقوم بشكل أساسي بإنشاء عرض PowerPoint تقديمي يحتوي على شرائح بناءً على صور JPG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل JPG إلى PPTX في C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ثبّت ** Aspose.Slides for .NET **. راجع [** التثبيت **](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل صورة JPG التي تريد تحويلها إلى PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف الناتج كعرض تقديمي PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="مبني باستخدام Aspose.Slides" title="تحويل JPG إلى PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Conversion المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات JPG الخاصة بك." button="افتح Aspose.Slides Conversion" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" upload="أفلت ملفك أو ارفعه" saveAs="حفظ بتنسيق" convert="تحويل" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحوّل Aspose.Slides الملفات قبل أن تكتب الكود.
- ارفع ملفات JPG واحفظها بتنسيق PPTX.
- نزّل النتيجة أو حوّل المزيد من الملفات.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويلات PowerPoint المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل الملفات بتنسيقات أخرى إلى PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
