---
title: إزالة ODP Annotation باستخدام Java
weight: 1790
url: /ar/java/annotation/odp/ 
description: نموذج كود Java لحذف التعليقات التوضيحية بتنسيق ODP على Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="إزالة التعليقات ومؤلفو التعليقات من ODP في Java" h2="قم ببناء تطبيقات Java الخاصة بك للتعامل مع التعليقات والمؤلفين في ملفات المستندات باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="إزالة التعليقات من ODP عبر Java" %}}
لإزالة التعليقات التوضيحية من ملف ODP ، سنستخدم [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/) واجهة برمجة تطبيقات غنية بالميزات وقوية وسهلة الاستخدام واجهة برمجة تطبيقات معالجة المستندات لمنصة جافا.
{{% blocks/products/pf/agp/code-block title="حذف التعليقات التوضيحية من ODP - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.odp");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إزالة التعليقات من ODP عبر Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت ** Aspose.Slides for Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل ODP بنسخة من فئة العرض التقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
كرر على جميع مؤلفي ODP المحملة
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
إزالة جميع تعليقات المؤلف
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
إزالة جميع المؤلفين في النهاية
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات التعليقات التوضيحية الأخرى المعتمدة" subTitle="باستخدام Java ، يمكن للمرء أن يعلق بسهولة على التنسيقات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}