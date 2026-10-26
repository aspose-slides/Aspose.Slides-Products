---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: البحث عن النص في ملفات عروض ODP التقديمية باستخدام .NET
url: /ar/net/search/odp/
description: كود مصدري بلغة C# للبحث عن النص في عروض ODP التقديمية.
keywords: البحث عن النص في ODP، العثور على النص في ODP، البحث في نص عرض ODP التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="البحث عن النص في ملفات ODP باستخدام C#" h2="أنشئ تطبيقات .NET تعثر على النص في العروض التقديمية باستخدام واجهات API من جانب الخادم." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="البحث عن النص في عرض ODP تقديمي باستخدام C#" variant="code" %}}

باستخدام [Aspose.Slides for .NET](/slides/ar/net/)، يمكنك البحث عن النص في عرض ODP تقديمي. احصل على إطارات النص في شريحة باستخدام `SlideUtil.GetAllTextBoxes`، ثم افحص قيم `Text` الخاصة بها بحثًا عن العبارة المطلوبة.

{{< blocks/products/pf/slides-design-update-10-2026/code title="البحث عن النص في عرض ODP تقديمي باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية البحث عن النص في عرض ODP تقديمي باستخدام C#" intro="اتبع هذه الخطوات للبحث عن النص في عرض ODP تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف ODP باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على الشريحة المطلوبة من `Presentation.Slides` وأسندها إلى متغير.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على إطارات النص الخاصة بها باستخدام [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تحقق مما إذا كانت قيمة `Text` لكل إطار تحتوي على العبارة المطلوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="مبني باستخدام Aspose.Slides" title="البحث عن النص في ملفات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Search المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Search" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يعثر Aspose.Slides على النص قبل أن تكتب الكود.
- ابحث في ملف ODP عن نص عادي أو تعبيرات نمطية.
- نزّل النتائج كملف نصي.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للبحث" subTitle="باستخدام C#، يمكنك أيضًا البحث عن النص في التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
