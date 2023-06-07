---
title: فتح ملفات PPT العروض التقديمية باستخدام Java
url: /ar/java/unlock/ppt/
keywords: إزالة الحماية ضد الكتابة PPT ، وفك تشفير PPT ، وإلغاء تأمين PPT Presentation ، وإلغاء الحماية PPT
description: Java شفرة المصدر لإزالة الحماية من العرض التقديمي PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="فتح PPT باستخدام Java" h2="أنشئ تطبيقات Java الخاصة بك لإزالة كلمات المرور من PowerPoint وفك تشفير ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="إزالة التشفير من العرض التقديمي PPT عبر Java" %}}
باستخدام Aspose.Slides for Java ، يمكنك إزالة التشفير أو الحماية بكلمة مرور على العرض التقديمي PPT. بهذه الطريقة ، يصبح المستخدمون قادرين على الوصول إلى العرض التقديمي PPT أو تعديله دون قيود.
{{% blocks/products/pf/agp/code-block title="تعطيل الحماية بكلمة مرور من PPT باستخدام Java" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="إزالة الحماية ضد الكتابة من العرض التقديمي PPT باستخدام Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إزالة كلمة المرور من PPT عبر Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات إزالة الحماية من ملفات PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPT بمثيل عرض تقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
إزالة الحماية ضد الكتابة باستخدام فئة ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="التنسيقات الأخرى المدعومة" subTitle="باستخدام Java ، يمكنك أيضًا إزالة الحماية من التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}