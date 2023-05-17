---
title: قم بتنقيح PPTX لملفات العروض التقديمية باستخدام C++
url: /ar/cpp/redaction/pptx/
keywords: تنقيح PPTX والعثور على النص واستبداله في PPTX وتحديث PPTX Presentation
description: C++ شفرة المصدر للبحث عن النص واستبداله في العرض التقديمي PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="تنقيح PPTX باستخدام C++" h2="أنشئ تطبيقات C++ الخاصة بك للبحث عن نص واستبداله في ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم. تعرف على كيفية البحث عن نص واستبداله في المحتوى أو التعليقات أو البيانات الوصفية للعروض التقديمية PPTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="تنقيح PPTX العرض التقديمي عبر C++" %}}
يمكن إجراء بحث أساسي عن المستند واستبدال النص في المحتويات أو التعليقات أو ملاحظات الشرائح أو البيانات الوصفية باستخدام واجهات برمجة تطبيقات Aspose.Slides for C++ باستخدام سطور قليلة فقط من التعليمات البرمجية. ابحث عن النص واستبدله في PowerPoint و OpenOffice. تحرير النص والتعليقات والبيانات الوصفية في العرض التقديمي عبر مطابقة بيانات regexp.
{{% blocks/products/pf/agp/code-block title="تنقيح PPTX العرض التقديمي باستخدام C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تنقيح PPTX عبر C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لتنقيح ملفات PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPTX بمثيل عرض تقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
استخدم طريقة [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) للبحث عن النص واستبداله.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="عبر الإنترنت PPTX عروض توضيحية مباشرة للتنقيح" sectionDescription="ابحث واستبدل النص في المحتويات أو التعليقات أو البيانات الوصفية في مستندات PPTX الآن." >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات Redact المدعومة الأخرى" subTitle="باستخدام C++ ، يمكنك أيضًا تنقيح التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}