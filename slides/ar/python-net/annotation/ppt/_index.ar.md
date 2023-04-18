---
title: إزالة تعليق PPT التوضيحي باستخدام Python
weight: 4380
url: /ar/python-net/annotation/ppt/ 
description: كود مصدر Python لإزالة تعليقات عرض PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="إزالة التعليقات ومؤلفو التعليقات من PPT في Python" h2="أنشئ نصوص Python النصية الخاصة بك للتعامل مع التعليقات والمؤلفين في ملفات المستندات باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="إزالة التعليقات من PPT عبر Python" %}}
لإزالة التعليقات التوضيحية من ملف PPT ، سنستخدم [Aspose.Slides for Python عبر .NET](https://products.aspose.com/slides/ar/python-net/) واجهة برمجة تطبيقات غنية بالميزات ، واجهة برمجة تطبيقات معالجة المستندات قوية وسهلة الاستخدام لمنصة Python.
{{% blocks/products/pf/agp/code-block title="حذف التعليقات التوضيحية من PPT - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.ppt") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إزالة التعليقات من PPT عبر Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ثبّت ** Aspose.Slides for Python عبر .NET **. راجع [** التثبيت **](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل PPT بمثيل لفئة العرض التقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
كرر على جميع مؤلفي تحميل PPT
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

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات التعليقات التوضيحية الأخرى المعتمدة" subTitle="باستخدام Python ، يمكن للمرء بسهولة التعليق على التنسيقات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}