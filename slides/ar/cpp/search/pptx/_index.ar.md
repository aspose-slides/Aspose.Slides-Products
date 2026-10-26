---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: البحث عن النص في عروض PPTX التقديمية باستخدام C++
url: /ar/cpp/search/pptx/
description: ابحث عن النص في عروض PPTX التقديمية بلغة C++. استخدم Aspose.Slides for C++ للعثور على النص في ملفات العروض التقديمية.
keywords: البحث عن الكلمات في PPTX، العثور على النص في PPTX، البحث في نص عرض PPTX التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="البحث عن النص في PPTX باستخدام C++" h2="استخدم Aspose.Slides for C++ للعثور على النص في ملفات العروض التقديمية دون Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="البحث عن النص في عرض PPTX تقديمي عبر C++" variant="code" %}}

يتيح لك Aspose.Slides for C++ البحث عن النص في عروض PPTX التقديمية. استخدم `SlideUtil::GetAllTextBoxes` لجمع إطارات النص في شريحة، ثم تحقق مما إذا كان نصها يحتوي على العبارة المطلوبة.

{{< blocks/products/pf/slides-design-update-10-2026/code title="البحث عن النص في عرض PPTX تقديمي باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية البحث عن النص في PPTX عبر C++" intro="اتبع هذه الخطوات للبحث عن النص في عرض PPTX تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPTX باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على الشريحة المطلوبة باستخدام `Presentation::get_Slides` واحصل على إطارات النص الخاصة بها باستخدام [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تحقق مما إذا كان نص كل إطار يحتوي على العبارة المطلوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="مبني باستخدام Aspose.Slides" title="البحث عن النص في ملفات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Search المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Search" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يعثر Aspose.Slides على النص قبل أن تكتب الكود.
- ابحث في ملف PPTX عن نص عادي أو تعبيرات نمطية.
- نزّل النتائج كملف نصي.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للبحث" subTitle="باستخدام C++، يمكنك أيضًا البحث عن النص في التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
