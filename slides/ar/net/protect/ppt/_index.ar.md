---
title: حماية PPT ملفات العروض التقديمية باستخدام .NET
url: /ar/net/protect/ppt/
keywords: حماية الكتابة PPT ، تشفير PPT ، تأمين PPT Presentation ، Protect PPT
description: C# شفرة المصدر لحماية العرض التقديمي PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="القفل أو الحماية بكلمة مرور PPT باستخدام C#" h2="أنشئ تطبيقات .NET الخاصة بك لحماية ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="حماية عرض PPT عبر C#" %}}
باستخدام Aspose.Slides for .NET ، يمكنك حماية العرض التقديمي PPT من الفتح أو التعديل عن طريق تعيين كلمة مرور. بعد ذلك ، لفتح العرض التقديمي المقفل أو تعديله ، يجب على المستخدم توفير كلمة المرور.
{{% blocks/products/pf/agp/code-block title="تشفير عرض تقديمي PPT باستخدام C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="إعداد الحماية ضد الكتابة في عرض تقديمي PPT باستخدام C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية حماية كلمة المرور PPT عبر C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات حماية ملفات PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPT بمثيل عرض تقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حماية العرض التقديمي باستخدام فئة ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الحماية المدعومة الأخرى" subTitle="باستخدام C# ، يمكنك أيضًا حماية التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}