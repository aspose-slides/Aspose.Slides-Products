---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2290
title: استخراج النص من عروض PPTX التقديمية باستخدام C++
url: /ar/cpp/parser/pptx/ 
description: استخرج النص من عروض PPTX التقديمية في C++. استخدم Aspose.Slides for C++ لتحليل الشرائح وإطارات النص والفقرات وأجزاء النص.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحليل عروض PPTX التقديمية في C++" h2="استخدم Aspose.Slides for C++ لاستخراج النص من شرائح العرض التقديمي دون Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحليل ملف PPTX باستخدام C++" %}}

استخدم Aspose.Slides for C++ لتحليل ملفات عروض PPTX التقديمية واستخراج النص من الشرائح. توفر الواجهة البرمجية نص الشرائح عبر `SlideUtil::GetAllTextBoxes` و`ITextFrame` و`IParagraph` و`IPortion`، لذا يمكنك قراءة المحتوى النصي دون أتمتة Microsoft PowerPoint. ثبّت الحزمة [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) من NuGet أو استخدم الأمر أدناه في Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="الأمر" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="تحليل ملفات PPTX – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحليل ملفات PPTX في C++" intro="استخرج النص من ملفات PPTX باستخدام Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPTX باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على كائنات `ITextFrame` من الشريحة الأولى باستخدام `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على كائنات `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على كائنات `IParagraph` في كل `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على كائنات `IPortion` في كل `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اقرأ النص باستخدام `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يدعم Aspose.Slides for C++ منصات سطح المكتب والخوادم الرئيسية. تأكد من أن مشروعك يستوفي المتطلبات الأساسية التالية." %}}

-  Microsoft Windows أو Linux أو macOS أو نظام تشغيل متوافق آخر مع بيئة تشغيل C++ المدعومة.
-  مكتبة Aspose.Slides for C++ مضافة كمرجع في مشروعك.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="مبني باستخدام Aspose.Slides" title="استخراج النص والصور عبر الإنترنت" description="تطبيق Aspose.Slides Parser المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Parser" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يقرأ Aspose.Slides ملفاتك قبل كتابة الكود.
- ارفع ملف PPTX واحصل على نصه وصوره.
- نزّل كل شيء في أرشيف ZIP واحد.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

A PPTX file is a Microsoft PowerPoint Open XML presentation file. It stores slides, text, images, formatting, animations, and other presentation content in a zipped XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتحليل" subTitle="باستخدام C++ يمكنك أيضًا تحليل تنسيقات عروض تقديمية أخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/parser/odp/" name="ODP" description="عرض OpenDocument التقديمي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/parser/ppt/" name="PPT" description="عرض PowerPoint 97-2003 التقديمي" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
