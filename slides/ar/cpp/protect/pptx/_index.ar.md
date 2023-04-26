---
title: حماية PPTX ملفات العروض التقديمية باستخدام C++
url: /ar/cpp/protect/pptx/
keywords: حماية الكتابة PPTX ، تشفير PPTX ، تأمين PPTX Presentation ، Protect PPTX
description: C++ شفرة المصدر لحماية العرض التقديمي PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="القفل أو الحماية بكلمة مرور PPTX باستخدام C++" h2="أنشئ تطبيقات C++ الخاصة بك لحماية ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="حماية عرض PPTX عبر C++" %}}
باستخدام Aspose.Slides for C++ ، يمكنك حماية العرض التقديمي PPTX من الفتح أو التعديل عن طريق تعيين كلمة مرور. بعد ذلك ، لفتح العرض التقديمي المقفل أو تعديله ، يجب على المستخدم توفير كلمة المرور.
{{% blocks/products/pf/agp/code-block title="تشفير عرض تقديمي PPTX باستخدام C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="إعداد الحماية ضد الكتابة في عرض تقديمي PPTX باستخدام C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية حماية كلمة المرور PPTX عبر C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات حماية ملفات PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPTX بمثيل عرض تقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حماية العرض التقديمي باستخدام فئة ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الحماية المدعومة الأخرى" subTitle="باستخدام C++ ، يمكنك أيضًا حماية التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}