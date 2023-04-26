---
title: حماية PPTX ملفات العروض التقديمية باستخدام Java
url: /ar/java/protect/pptx/
keywords: حماية الكتابة PPTX ، تشفير PPTX ، تأمين PPTX Presentation ، Protect PPTX
description: Java شفرة المصدر لحماية العرض التقديمي PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="القفل أو الحماية بكلمة مرور PPTX باستخدام Java" h2="أنشئ تطبيقات Java الخاصة بك لحماية ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="حماية عرض PPTX عبر Java" %}}
باستخدام Aspose.Slides for Java ، يمكنك حماية العرض التقديمي PPTX من الفتح أو التعديل عن طريق تعيين كلمة مرور. بعد ذلك ، لفتح العرض التقديمي المقفل أو تعديله ، يجب على المستخدم توفير كلمة المرور.
{{% blocks/products/pf/agp/code-block title="تشفير عرض تقديمي PPTX باستخدام Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="إعداد الحماية ضد الكتابة في عرض تقديمي PPTX باستخدام Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية حماية كلمة المرور PPTX عبر Java" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الحماية المدعومة الأخرى" subTitle="باستخدام Java ، يمكنك أيضًا حماية التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}