---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: عرض ملفات ODP باستخدام C#
keywords: عرض ODP, فتح ODP, عارض ODP, ODP, C# API, مكتبة .NET
weight: 8370
url: /ar/net/viewer/odp/ 
description: اعرض ملفات ODP باستخدام C#. استخدم Aspose.Slides for .NET لفتح ملفات العروض التقديمية وحفظها بتنسيق HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="عرض ملفات ODP باستخدام C#" h2="واجهة برمجة تطبيقات C# لفتح ملفات ODP وحفظها بتنسيق HTML متجاوب."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="عرض ملفات ODP باستخدام Aspose.Slides" %}}

لعرض ملفات ODP، استخدم واجهة برمجة التطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي واجهة برمجة تطبيقات غنية بالميزات وقوية وسهلة الاستخدام للغة C#. افتح مدير الحزم [NuGet](https://www.nuget.org/packages/aspose.slides.net)، وابحث عن **Aspose.Slides** وثبّته. يمكنك أيضًا تشغيل الأمر التالي في Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="أمر Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

باستخدام [**Aspose.Slides for .NET**](/slides/ar/net/)، يمكنك تحميل ملف ODP وحفظه بتنسيق HTML متجاوب ببضعة أسطر من الكود.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود C# لعرض ملفات ODP" >}}
```cs
using var presentation = new Presentation("presentation.odp");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية عرض ملفات ODP باستخدام C#" intro="يتيح Aspose.Slides للمطورين عرض ملفات ODP ببضعة أسطر من الكود فقط." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت **Aspose.Slides for .NET**. راجع [**التثبيت**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف `ODP` باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أنشئ كائن `ResponsiveHtmlController` للحصول على مخرجات HTML متجاوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أنشئ كائن `HtmlOptions` واضبط الخاصية `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ ملف ODP بتنسيق HTML باستخدام `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يدعم Aspose.Slides for .NET جميع أنظمة التشغيل الرئيسية. تأكد من توفر المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin
- بيئة تطوير مثل Microsoft Visual Studio
- إضافة مرجع إلى Aspose.Slides for .NET في مشروعك

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="مبني باستخدام Aspose.Slides" title="عرض ملفات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Viewer المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Viewer" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يعرض Aspose.Slides ملفاتك قبل كتابة الكود.
- ارفع ملف ODP واعرض شرائحه فورًا.
- يعمل على أجهزة الكمبيوتر والهواتف المحمولة دون الحاجة إلى PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

تستخدم الملفات ذات الامتداد `.ODP` تنسيق OpenDocument Presentation المحدد في معيار OASIS OpenDocument. يحتوي ملف ODP على مجموعة من الشرائح التي قد تتضمن نصوصًا وصورًا وتنسيقات ورسومًا متحركة ووسائط أخرى. ويمكن للتطبيقات التي تدعم عروض OpenDocument التقديمية، مثل LibreOffice Impress و Apache OpenOffice Impress، فتح ملفات ODP.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="عرض ملفات أخرى" subTitle="يمكنك أيضًا فتح العروض التقديمية بتنسيقات أخرى وعرضها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/otp/" name="OTP" description="قالب عرض OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pot/" name="POT" description="قالب PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/potm/" name="POTM" description="قالب PowerPoint مُمكَّن بوحدات الماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/potx/" name="POTX" description="قالب PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pps/" name="PPS" description="عرض شرائح PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/ppsm/" name="PPSM" description="عرض شرائح PowerPoint مُمكَّن بوحدات الماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/ppsx/" name="PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/ppt/" name="PPT" description="عرض PowerPoint 97-2003 التقديمي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pptm/" name="PPTM" description="عرض PowerPoint تقديمي مُمكَّن بوحدات الماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/viewer/pptx/" name="PPTX" description="عرض PowerPoint التقديمي" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
