---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: دمج ملفات ODP عبر .NET
weight: 4610
url: /ar/net/merger/odp/ 
description: كود المصدر C# لدمج مستندات ODP على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="دمج تنسيقات ODP في C#" h2="دمج مستندات ODP أصلي وعالي الأداء باستخدام Aspose.Slides من جانب الخادم لـ .NET APIs ، دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية دمج ملف ODP باستخدام C#" %}}

من أجل دمج ملف ODP ، سنستخدم
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="دمج ملفات ODP - C#" >}}
```cs
var ps1 = new Presentation("presen1.odp");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first ODP presentation is added with its own styles.
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات دمج ملفات ODP في C#" intro="يمكن دمج ودمج المستندات الأساسية مع واجهات برمجة التطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net) ببضعة سطور من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل جميع ملفات ODP بالمسار الكامل.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اجعل مستندًا واحدًا كملف أساسي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء الطريقة المناسبة لتسلسل ودمج الملفات واحدًا تلو الآخر.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعاء طريقة Save () ومرر اسم الملف (المسار الكامل) والشكل (ODP) كمعامل.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}يمكنك الآن فتح ملف ODP واستخدامه في Microsoft Office أو Adobe PDF أو أي برنامج آخر متوافق.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

تستخدم الملفات ذات الامتداد `.ODP` تنسيق OpenDocument Presentation المحدد في معيار OASIS OpenDocument. يحتوي ملف ODP على مجموعة من الشرائح التي قد تتضمن نصوصًا وصورًا وتنسيقات ورسومًا متحركة ووسائط أخرى. ويمكن للتطبيقات التي تدعم عروض OpenDocument التقديمية، مثل LibreOffice Impress و Apache OpenOffice Impress، فتح ملفات ODP.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات الدمج المدعومة الأخرى" subTitle="باستخدام C# ، يمكن للمرء أيضًا دمج العديد من تنسيقات الملفات الأخرى بما في ذلك." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/otp/" name="OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/pot/" name="POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/potm/" name="POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/potx/" name="POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/pps/" name="PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/ppsm/" name="PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/ppsx/" name="PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/ppt/" name="PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/pptm/" name="PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/merger/pptx/" name="PPTX" description="افتح تنسيق عرض XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
