---
title: فتح ملفات ODP العروض التقديمية باستخدام C++
url: /ar/cpp/unlock/odp/
keywords: إزالة الحماية ضد الكتابة ODP ، وفك تشفير ODP ، وإلغاء تأمين ODP Presentation ، وإلغاء الحماية ODP
description: C++ شفرة المصدر لإزالة الحماية من العرض التقديمي ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="فتح ODP باستخدام C++" h2="أنشئ تطبيقات C++ الخاصة بك لإزالة كلمات المرور من PowerPoint وفك تشفير ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="إزالة التشفير من العرض التقديمي ODP عبر C++" %}}
باستخدام Aspose.Slides for C++ ، يمكنك إزالة التشفير أو الحماية بكلمة مرور على العرض التقديمي ODP. بهذه الطريقة ، يصبح المستخدمون قادرين على الوصول إلى العرض التقديمي ODP أو تعديله دون قيود.
{{% blocks/products/pf/agp/code-block title="تعطيل الحماية بكلمة مرور من ODP باستخدام C++" offSpacer="true" %}}

```cpp

auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"123123");
    
auto presentation = System::MakeObject<Presentation>(u"pres.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"encryption-removed.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="إزالة الحماية ضد الكتابة من العرض التقديمي ODP باستخدام C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إزالة كلمة المرور من ODP عبر C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات إزالة الحماية من ملفات ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل ODP بمثيل عرض تقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
إزالة الحماية ضد الكتابة باستخدام فئة ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="التنسيقات الأخرى المدعومة" subTitle="باستخدام C++ ، يمكنك أيضًا إزالة الحماية من التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}