---
title: تحرير PPT في Python
url: /ar/python-net/editor/ppt/
keywords: تحرير PPT ، تحرير PowerPoint ، PPT ، PowerPoint ، Python API ، مكتبة Python
description: تحرير PPT في Python. استخدم مكتبة Python API لتحرير عرض PowerPoint التقديمي
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحرير PPT في Python" h2="مكتبة Python عالية السرعة ومتعددة المنصات لتحرير PPT باستخدام كود Python" >}}

{{% blocks/products/pf/feature-page-section h2="تحرير PPT باستخدام Aspose.Slides" %}}

[** Aspose.Slides for Python عبر .NET **](https://products.aspose.com/slides/ar/python-net/) هي مكتبة Python قوية تُستخدم لمعالجة العروض التقديمية وتحريرها. يمكنك تحرير عرض PPT عن طريق إضافة سطر جديد من النص إليه. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="تحرير PPT في Python" %}}
باستخدام [** Aspose.Slides for Python عبر .NET **](https://products.aspose.com/slides/ar/python-net/) ، يمكنك إضافة سطر جديد من النص إلى مستند PPT بعدد قليل فقط أسطر من التعليمات البرمجية.

{{% blocks/products/pf/agp/code-block title="كود Python لتحرير PPT" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحرير PPT في Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ثبّت ** Aspose.Slides for Python عبر .NET **. راجع [** التثبيت **](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف المكتبة كمرجع في مشروعك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل العرض التقديمي PPT الذي تريد تحريره.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف سطرًا جديدًا من النص.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ ملف PowerPoint الذي تم تغييره.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="قم بتحرير الملفات الأخرى" subTitle="يمكنك أيضًا تحرير الملفات بتنسيقات أخرى" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}