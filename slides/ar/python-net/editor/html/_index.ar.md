---
title: تحرير HTML في Python
url: /ar/python-net/editor/html/
keywords: تحرير HTML ، HTML ، Python API ، مكتبة Python
description: تحرير HTML في Python. استخدم مكتبة Python API لتحرير ملف HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحرير HTML في Python" h2="مكتبة Python عالية السرعة ومتعددة المنصات لتحرير HTML باستخدام كود Python" >}}

{{% blocks/products/pf/feature-page-section h2="تحرير HTML باستخدام Aspose.Slides" %}}

[** Aspose.Slides for Python عبر .NET **](https://products.aspose.com/slides/ar/python-net/) هي مكتبة Python قوية تُستخدم لمعالجة وتحرير العروض التقديمية ومستندات HTML والملفات الأخرى . يمكنك تحرير مستند HTML عن طريق إضافة سطر جديد من النص إليه. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="تحرير HTML في Python" %}}
باستخدام [** Aspose.Slides for Python عبر .NET **](https://products.aspose.com/slides/ar/python-net/) ، يمكنك إضافة سطر جديد من النص إلى مستند HTML بعدد قليل فقط أسطر من التعليمات البرمجية.

{{% blocks/products/pf/agp/code-block title="كود Python لتحرير HTML" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحرير HTML في Python" >}}


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
قم بتحميل مستند HTML الذي تريد تحريره.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف سطرًا جديدًا من النص.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ ملف HTML الذي تم تغييره.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="قم بتحرير الملفات الأخرى" subTitle="يمكنك أيضًا تحرير الملفات بتنسيقات أخرى" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}