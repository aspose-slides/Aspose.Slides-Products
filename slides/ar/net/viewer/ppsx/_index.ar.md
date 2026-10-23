---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: عرض ملفات PPSX باستخدام C#
keywords: عرض PPSX, فتح PPSX, عارض PPSX, PPSX, PowerPoint, C# API, مكتبة .NET
weight: 2370
url: /ar/net/viewer/ppsx/ 
description: اعرض ملفات PPSX باستخدام C#. استخدم Aspose.Slides for .NET لفتح ملفات العروض التقديمية وحفظها بتنسيق HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="عرض ملفات PPSX باستخدام C#" h2="واجهة برمجة تطبيقات C# لفتح ملفات PPSX وحفظها بتنسيق HTML متجاوب."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="عرض ملفات PPSX باستخدام Aspose.Slides" %}}

لعرض ملفات PPSX، استخدم واجهة برمجة التطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي واجهة برمجة تطبيقات غنية بالميزات وقوية وسهلة الاستخدام للغة C#. افتح مدير الحزم [NuGet](https://www.nuget.org/packages/aspose.slides.net)، وابحث عن **Aspose.Slides** وثبّته. يمكنك أيضًا تشغيل الأمر التالي في Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="أمر Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

باستخدام [**Aspose.Slides for .NET**](/slides/ar/net/)، يمكنك تحميل ملف PPSX وحفظه بتنسيق HTML متجاوب ببضعة أسطر من الكود.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود C# لعرض ملفات PPSX" >}}
```cs
using var presentation = new Presentation("presentation.ppsx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية عرض ملفات PPSX باستخدام C#" intro="يتيح Aspose.Slides للمطورين عرض ملفات PPSX ببضعة أسطر من الكود فقط." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت **Aspose.Slides for .NET**. راجع [**التثبيت**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف `PPSX` باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أنشئ كائن `ResponsiveHtmlController` للحصول على مخرجات HTML متجاوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أنشئ كائن `HtmlOptions` واضبط الخاصية `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ ملف PPSX بتنسيق HTML باستخدام `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يدعم Aspose.Slides for .NET جميع أنظمة التشغيل الرئيسية. تأكد من توفر المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin
- بيئة تطوير مثل Microsoft Visual Studio
- إضافة مرجع إلى Aspose.Slides for .NET في مشروعك

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="مبني باستخدام Aspose.Slides" title="عرض ملفات PPSX عبر الإنترنت" description="تطبيق Aspose.Slides Viewer المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPSX الخاصة بك." button="افتح Aspose.Slides Viewer" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يعرض Aspose.Slides ملفاتك قبل كتابة الكود.
- ارفع ملف PPSX واعرض شرائحه فورًا.
- يعمل على أجهزة الكمبيوتر والهواتف المحمولة دون الحاجة إلى PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="عرض ملفات أخرى" subTitle="يمكنك أيضًا فتح العروض التقديمية بتنسيقات أخرى وعرضها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/odp/" name="ODP" description="عرض OpenDocument التقديمي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/otp/" name="OTP" description="قالب عرض OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pot/" name="POT" description="قالب PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/potm/" name="POTM" description="قالب PowerPoint مُمكَّن بوحدات الماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/potx/" name="POTX" description="قالب PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pps/" name="PPS" description="عرض شرائح PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/ppsm/" name="PPSM" description="عرض شرائح PowerPoint مُمكَّن بوحدات الماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/ppt/" name="PPT" description="عرض PowerPoint 97-2003 التقديمي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pptm/" name="PPTM" description="عرض PowerPoint تقديمي مُمكَّن بوحدات الماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pptx/" name="PPTX" description="عرض PowerPoint التقديمي" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
