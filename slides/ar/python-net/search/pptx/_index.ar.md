---
title: البحث عن نص في PPTX ملفات العروض التقديمية باستخدام Python
url: /ar/python-net/search/pptx/
keywords: كلمات البحث في PPTX ، البحث عن النص واستبداله في PPTX ، البحث عن النص PPTX Presentation
description: Python شفرة المصدر للبحث عن النص في PPTX Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="بحث عن نص PPTX باستخدام Python" h2="أنشئ تطبيقات Python الخاصة بك للبحث عن نص واستبداله في ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم. تعرف على كيفية العثور على جميع مداخل كلمة أو عبارة معينة في مستندات العرض التقديمي. نص البحث عن طريق مطابقة البيانات بدقة ومطابقة التعبير العادي." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="البحث عن نص واستبداله PPTX العرض التقديمي عبر Python" %}}
يمكن إجراء بحث أساسي عن المستند واستبدال النص في المحتويات أو التعليقات أو ملاحظات الشرائح أو البيانات الوصفية باستخدام واجهات برمجة تطبيقات Aspose.Slides for Python via .NET باستخدام سطور قليلة فقط من التعليمات البرمجية. استخدم مطابقة التعبير العادي ، تطابق الحالة للبحث عن نص في العرض التقديمي. نص البحث في العناوين أو المحتوى أو التذييل أو رأس الصفحة.
{{% blocks/products/pf/agp/code-block title="بحث عن نص PPTX عرض تقديمي باستخدام Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية البحث عن نص بتنسيق PPTX عبر Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات البحث عن ملفات PPTX النصية." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPTX بمثيل عرض تقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
استخدم طريقة [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) للبحث عن النص واستبداله.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="عبر الإنترنت PPTX ابحث في العروض التوضيحية المباشرة" sectionDescription="ابحث واستبدل النص في المحتويات أو التعليقات أو البيانات الوصفية في مستندات PPTX الآن." >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات البحث الأخرى المدعومة" subTitle="باستخدام Python ، يمكنك أيضًا البحث عن نص بالتنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}