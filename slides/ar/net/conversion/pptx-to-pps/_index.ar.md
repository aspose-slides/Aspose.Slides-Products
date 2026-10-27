---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPTX إلى PPS عبر C#
weight: 2590
url: /ar/net/conversion/pptx-to-pps/ 
description: رمز عينة لتحويل PPTX إلى PPS C#. استخدم رمز مثال API لملفات PPTX الدفعية لتحويل PPS داخل VB.NET أو Asp.NET أو أي تطبيق قائم على .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPTX إلى PPS عبر C#" h2="تصدير ملفات PowerPoint® PPTX إلى PPS على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية تحويل PPTX إلى PPS باستخدام C#" %}}

من أجل تحويل PPTX إلى PPS ، سنستخدم
 [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net)
 واجهة برمجة التطبيقات API وهي غنية بالميزات وقوية وسهلة الاستخدام للتعامل مع المستندات وتحويلها API لمنصة C#. يفتح
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 مدير الحزم ، ابحث عن
 ينزلق
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="أمر وحدة تحكم مدير الحزم" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="يوضح نموذج الشفرة هذا تحويل PPTX إلى PPS C#" >}}
```cs
// instantiate a Presentation object that represents a PPTX file
var presentation = new Presentation("template.pptx");
// save the presentation as PPS
presentation.Save("output.pps", SaveFormat.Pps); 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات تحويل PPTX إلى PPS عبر C#" intro="يمكن لمطوري .NET تحميل وتحويل ملفات PPTX بسهولة إلى PPS في بضعة أسطر من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف PPTX بنسخة من فئة العرض التقديمي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعاء الأسلوب Save أثناء تحديد مسار ملف الإخراج & SaveFormat.Pps كمعلمات{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سيتم حفظ ملف PPS في المسار المحدد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل التعليمات البرمجية المصدر عينة التحويل .NET ، تأكد من أن لديك المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
- بيئة التطوير مثل Microsoft Visual Studio.
- Aspose.Slides لـ .NET DLL المشار إليها في مشروعك.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="مبني باستخدام Aspose.Slides" title="تحويل PPTX إلى PPS عبر الإنترنت" description="تطبيق Aspose.Slides Conversion المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Conversion" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" upload="أفلت ملفك أو ارفعه" saveAs="حفظ بتنسيق" convert="تحويل" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحوّل Aspose.Slides الملفات قبل أن تكتب الكود.
- ارفع ملفات PPTX واحفظها بتنسيق PPS.
- نزّل النتيجة أو حوّل المزيد من الملفات.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PPTX إلى العديد من تنسيقات الملفات الأخرى بما في ذلك القليل منها المدرجة أدناه." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="سيب" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-html/" name="PPTX TO HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="صورة JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="نموذج المستندات المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-png/" name="PPTX TO PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-pot/" name="PPTX TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="تنسيق SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
