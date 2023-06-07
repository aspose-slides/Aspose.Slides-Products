---
title: فتح ملفات ODP العروض التقديمية باستخدام Python
url: /ar/python-net/unlock/odp/
keywords: إزالة الحماية ضد الكتابة ODP ، وفك تشفير ODP ، وإلغاء تأمين ODP Presentation ، وإلغاء الحماية ODP
description: Python شفرة المصدر لإزالة الحماية من العرض التقديمي ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="فتح ODP باستخدام Python" h2="أنشئ تطبيقات Python الخاصة بك لإزالة كلمات المرور من PowerPoint وفك تشفير ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="إزالة التشفير من العرض التقديمي ODP عبر Python" %}}
باستخدام Aspose.Slides for Python via .NET ، يمكنك إزالة التشفير أو الحماية بكلمة مرور على العرض التقديمي ODP. بهذه الطريقة ، يصبح المستخدمون قادرين على الوصول إلى العرض التقديمي ODP أو تعديله دون قيود.
{{% blocks/products/pf/agp/code-block title="تعطيل الحماية بكلمة مرور من ODP باستخدام Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.odp", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="إزالة الحماية ضد الكتابة من العرض التقديمي ODP باستخدام Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.odp") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.odp", slides.export.SaveFormat.ODP)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إزالة كلمة المرور من ODP عبر Python" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="التنسيقات الأخرى المدعومة" subTitle="باستخدام Python ، يمكنك أيضًا إزالة الحماية من التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}