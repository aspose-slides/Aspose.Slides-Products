---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: دمج ملفات PPTM عبر .NET
weight: 5580
url: /ar/net/merger/pptm/ 
description: كود مصدر C# لدمج مستندات PPTM على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="دمج تنسيقات PPTM في C#" h2="دمج مستندات PPTM أصلي وعالي الأداء باستخدام Aspose.Slides من جانب الخادم لـ .NET APIs ، دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية دمج ملف PPTM باستخدام C#" %}}

من أجل دمج ملف PPTM ، سنستخدم
 [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net)
 API وهو غني بالميزات وقوي وسهل الاستخدام لمعالجة المستندات ودمجها API لمنصة C#. يفتح
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 مدير الحزم ، ابحث عن
 ** Aspose.Slides **
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="أمر" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="دمج ملفات PPTM - C#" >}}
```cs
var ps1 = new Presentation("presen1.pptm");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPTM presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات دمج ملفات PPTM في C#" intro="يمكن دمج ودمج المستندات الأساسية مع واجهات برمجة التطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net) ببضعة سطور من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل جميع ملفات PPTM بالمسار الكامل.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اجعل مستندًا واحدًا كملف أساسي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء الطريقة المناسبة لتسلسل ودمج الملفات واحدًا تلو الآخر.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء طريقة Save () وقم بتمرير اسم الملف (المسار الكامل) والتنسيق (PPTM) كمعامل.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}يمكنك الآن فتح واستخدام ملف PPTM في Microsoft Office أو Adobe PDF أو أي برنامج آخر متوافق.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يتم دعم واجهات برمجة التطبيقات الخاصة بنا على جميع الأنظمة الأساسية وأنظمة التشغيل الرئيسية. قبل تنفيذ الكود أدناه ، يرجى التأكد من أن لديك المتطلبات الأساسية التالية على نظامك." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية
- بيئة التطوير مثل Microsoft Visual Studio
- Aspose.Slides for .NET DLL المشار إليها في مشروعك - قم بالتثبيت من NuGet باستخدام الزر "تنزيل" أعلاه

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="دمج ملفات PDF على الإنترنت"
  description="[كيفية دمج ملفات PDF في بايثون](https://products.aspose.com/slides/ar/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

الملفات ذات الامتداد `.PPTM` هي ملفات عروض تقديمية تدعم وحدات الماكرو، وقد ظهرت مع Microsoft PowerPoint 2007. تشبه ملفات PPTX، لكن ملفات PPTM يمكنها تخزين شيفرة ماكرو VBA، بينما لا تستطيع ملفات PPTX ذلك. يمكن فتح ملفات PPTM وتحريرها في Microsoft PowerPoint. أما التنسيق المرتبط PPSM فيُفتح افتراضيًا في طريقة عرض الشرائح، لكن يمكن أيضًا فتحه في PowerPoint لتحريره. ومثل ملفات PPTX، يمكن أن تحتوي ملفات PPTM على نصوص وصور ومقاطع فيديو ومخططات ومحتوى عرض آخر.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات الدمج المدعومة الأخرى" subTitle="باستخدام C# ، يمكن للمرء أيضًا دمج العديد من تنسيقات الملفات الأخرى بما في ذلك." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/odp/" name="ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/otp/" name="OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/pot/" name="POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/potm/" name="POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/potx/" name="POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/pps/" name="PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/ppsm/" name="PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/ppsx/" name="PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/ppt/" name="PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/pptx/" name="PPTX" description="افتح تنسيق عرض XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
