---
title: قم بتنقيح PPT لملفات العروض التقديمية باستخدام Python
url: /ar/python-net/redaction/ppt/
keywords: تنقيح PPT والعثور على النص واستبداله في PPT وتحديث PPT Presentation
description: Python شفرة المصدر للبحث عن النص واستبداله في العرض التقديمي PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="تنقيح PPT باستخدام Python" h2="أنشئ تطبيقات Python الخاصة بك للبحث عن نص واستبداله في ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم. تعرف على كيفية البحث عن نص واستبداله في المحتوى أو التعليقات أو البيانات الوصفية للعروض التقديمية PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="تنقيح PPT العرض التقديمي عبر Python" %}}
يمكن إجراء بحث أساسي عن المستند واستبدال النص في المحتويات أو التعليقات أو ملاحظات الشرائح أو البيانات الوصفية باستخدام واجهات برمجة تطبيقات Aspose.Slides for Python via .NET باستخدام سطور قليلة فقط من التعليمات البرمجية. ابحث عن النص واستبدله في PowerPoint و OpenOffice. تحرير النص والتعليقات والبيانات الوصفية في العرض التقديمي عبر مطابقة بيانات regexp.
{{% blocks/products/pf/agp/code-block title="تنقيح PPT العرض التقديمي باستخدام Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تنقيح PPT عبر Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لتنقيح ملفات PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPT بمثيل عرض تقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
استخدم طريقة [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) للبحث عن النص واستبداله.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="عبر الإنترنت PPT عروض توضيحية مباشرة للتنقيح" sectionDescription="ابحث واستبدل النص في المحتويات أو التعليقات أو البيانات الوصفية في مستندات PPT الآن." >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات Redact المدعومة الأخرى" subTitle="باستخدام Python ، يمكنك أيضًا تنقيح التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}