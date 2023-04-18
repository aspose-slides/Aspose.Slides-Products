---
title: إزالة تعليق PPTX التوضيحي باستخدام .NET
weight: 4380
url: /ar/net/annotation/pptx/ 
description: التعليمات البرمجية المصدر C# لحذف التعليقات التوضيحية بتنسيق PPTX على الأنظمة الأساسية .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="إزالة التعليقات ومؤلفي التعليقات من PPTX في C#" h2="أنشئ تطبيقات .NET الخاصة بك للتعامل مع التعليقات والمؤلفين في ملفات المستندات باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="إزالة التعليقات من PPTX عبر C#" %}}
من أجل إزالة التعليقات التوضيحية من ملف PPTX ، سنستخدم [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net) واجهة برمجة تطبيقات غنية بالميزات وقوية وسهلة الاستخدام واجهة برمجة تطبيقات معالجة المستندات لمنصة C#.
{{% blocks/products/pf/agp/code-block title="حذف التعليقات التوضيحية من PPTX - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إزالة التعليقات من PPTX عبر C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ثبّت ** Aspose.Slides for .NET **. راجع [** التثبيت **](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل PPTX بمثيل لفئة العرض التقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
كرر على جميع مؤلفي PPTX المحملة
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

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات التعليقات التوضيحية الأخرى المعتمدة" subTitle="باستخدام C# ، يمكن للمرء بسهولة التعليق على التنسيقات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}