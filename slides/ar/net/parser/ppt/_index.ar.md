---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: استخراج النص من ملفات PPT باستخدام .NET
url: /ar/net/parser/ppt/ 
description: كود مصدر C# لاستخراج النص من ملفات PPT باستخدام .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحليل ملفات PPT باستخدام C#" h2="استخرج النص وافحص تنسيقه في ملفات PPT باستخدام واجهات .NET البرمجية على الخادم."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحليل ملف PPT باستخدام C#" %}}

استخدم [Aspose.Slides for .NET](/slides/ar/net/) لاستخراج النص من عروض PPT التقديمية. ثبّت الحزمة من [NuGet](https://www.nuget.org/packages/aspose.slides.net) أو شغّل الأمر التالي في Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="الأمر" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="تحليل ملفات PPT – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحليل ملفات PPT في C#" intro="لا يتطلب التحليل الأساسي للمستندات باستخدام واجهة [Aspose.Slides for .NET](/slides/ar/net/) البرمجية سوى بضعة أسطر من الكود." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPT باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على إطارات النص باستخدام `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على إطارات النص والفقرات وأجزاء النص.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اقرأ الخصائص `Text` و`FontHeight` و`LatinFont.FontName` حسب الحاجة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يلزم توفر بيئة تشغيل .NET مدعومة ومرجع إلى حزمة Aspose.Slides for .NET. يمكنك استخدام Visual Studio أو أي بيئة تطوير C# متوافقة أخرى." %}}

- بيئة متوافقة مع .NET Framework أو .NET أو Mono أو Xamarin
- بيئة تطوير C# مثل Visual Studio
- Aspose.Slides for .NET مثبتة من NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="مبني باستخدام Aspose.Slides" title="استخراج النص والصور عبر الإنترنت" description="تطبيق Aspose.Slides Parser المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Parser" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يقرأ Aspose.Slides ملفاتك قبل كتابة الكود.
- ارفع ملف PPT واحصل على نصه وصوره.
- نزّل كل شيء في أرشيف ZIP واحد.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

ملف PPT هو عرض تقديمي من Microsoft PowerPoint 97-2003 بتنسيق الملفات الثنائي. يحتوي على شرائح بها نصوص وقوائم نقطية وصور ووسائط متعددة وكائنات OLE مضمنة. تستخدم إصدارات PowerPoint الأحدث تنسيق PPTX المبني على Office Open XML. ويمكن لتطبيقات مثل OpenOffice Impress وApple Keynote إنشاء ملفات PPT أيضًا.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتحليل" subTitle="باستخدام C# يمكنك أيضًا تحليل التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/parser/odp/" name="ODP" description="عرض OpenDocument التقديمي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/parser/pptx/" name="PPTX" description="عرض PowerPoint Open XML التقديمي" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
