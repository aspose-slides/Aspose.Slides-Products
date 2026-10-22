---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحرير ملفات PPS عبر .NET
url: /ar/net/editor/pps/ 
description: كود المصدر C# لتحرير مستند PPS على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحرير تنسيقات PPS في C#" h2="تحرير مستندات PPS أصلي وعالي الأداء باستخدام Aspose.Slides من جانب الخادم لـ .NET APIs ، دون استخدام أي برنامج مثل Microsoft أو Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية تحرير ملف PPS باستخدام C#" %}}

من أجل تحرير ملف PPS ، سنستخدم <a href="https://products.aspose.com/slides/ar/net"> Aspose.Slides for .NET </a> API وهو غني بالميزات وقوي وسهل الاستخدام API لمنصة C# لأي محرر. افتح مدير الحزمة <a href="https://www.nuget.org/packages/aspose.slides.net"> NuGet </a> ، وابحث عن <b> Aspose.Slides </b> وثبته. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="أمر" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="تحرير ملفات PPS - C#" >}}
```cs
using var presentation = new Presentation("document.pps");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pps", SaveFormat.Pps);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات لتحرير ملفات PPS في C#" intro="تحرير مستند أساسي باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net) يمكن عمل واجهات برمجة التطبيقات ببضعة سطور من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPS باستخدام كائن `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على الشريحة والشكل المستهدفين من خلال المتغيرات.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حدّث النص من خلال `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي المعدَّل باستخدام `SaveFormat.Pps`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يتم دعم واجهات برمجة التطبيقات الخاصة بنا على جميع الأنظمة الأساسية وأنظمة التشغيل الرئيسية. قبل تنفيذ الكود أدناه ، يرجى التأكد من أن لديك المتطلبات الأساسية التالية على نظامك." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية
- بيئة التطوير مثل Microsoft Visual Studio
- Aspose.Slides for .NET DLL المشار إليها في مشروعك - قم بالتثبيت من NuGet باستخدام الزر "تنزيل" أعلاه

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
