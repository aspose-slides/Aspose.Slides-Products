---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تنقيح عروض ODP التقديمية باستخدام C++
url: /ar/cpp/redaction/odp/
description: نقِّح عروض ODP التقديمية بلغة C++. استخدم Aspose.Slides for C++ للبحث عن النص الحساس واستبداله في ملفات العروض التقديمية.
keywords: تنقيح ODP، البحث عن النص واستبداله في ODP، تحديث عرض ODP التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تنقيح ODP باستخدام C++" h2="استخدم Aspose.Slides for C++ للبحث عن النص الحساس واستبداله في ملفات العروض التقديمية دون Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تنقيح عرض ODP تقديمي عبر C++" variant="code" %}}

يتيح لك Aspose.Slides for C++ تنقيح عروض ODP التقديمية عبر استبدال النص الحساس في الشرائح. استخدم `SlideUtil::FindAndReplaceText` مع كائن `Presentation` للبحث في العرض التقديمي واستبدال النص المطابق قبل حفظ الملف المحدَّث.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تنقيح عرض ODP تقديمي باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تنقيح ODP عبر C++" intro="اتبع هذه الخطوات لتنقيح عرض ODP تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف ODP باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم الأسلوب [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) للبحث عن النص الحساس واستبداله.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف المنقَّح باستخدام `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="مبني باستخدام Aspose.Slides" title="تنقيح ملفات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Redaction المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Redaction" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يبحث Aspose.Slides عن النص ويستبدله قبل أن تكتب الكود.
- ابحث عن النص واستبدله في ملف ODP، بما في ذلك باستخدام التعبيرات النمطية.
- نزّل الملف المنقَّح.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتنقيح" subTitle="باستخدام C++، يمكنك أيضًا تنقيح التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
