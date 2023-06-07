---
title: فتح ملفات ODP العروض التقديمية باستخدام .NET
url: /ar/net/unlock/odp/
keywords: إزالة الحماية ضد الكتابة ODP ، وفك تشفير ODP ، وإلغاء تأمين ODP Presentation ، وإلغاء الحماية ODP
description: C# شفرة المصدر لإزالة الحماية من العرض التقديمي ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="فتح ODP باستخدام C#" h2="أنشئ تطبيقات .NET الخاصة بك لإزالة كلمات المرور من PowerPoint وفك تشفير ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="إزالة التشفير من العرض التقديمي ODP عبر C#" %}}
باستخدام Aspose.Slides for .NET ، يمكنك إزالة التشفير أو الحماية بكلمة مرور على العرض التقديمي ODP. بهذه الطريقة ، يصبح المستخدمون قادرين على الوصول إلى العرض التقديمي ODP أو تعديله دون قيود.
{{% blocks/products/pf/agp/code-block title="تعطيل الحماية بكلمة مرور من ODP باستخدام C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="إزالة الحماية ضد الكتابة من العرض التقديمي ODP باستخدام C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إزالة كلمة المرور من ODP عبر C#" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="التنسيقات الأخرى المدعومة" subTitle="باستخدام C# ، يمكنك أيضًا إزالة الحماية من التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}