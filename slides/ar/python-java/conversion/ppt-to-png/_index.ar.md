---
title: تحويل PPT إلى PNG في بايثون
url: /ar/python-java/conversion/ppt-to-png/
keywords: تحويل العروض التقديمية بايثون، تحويل العروض التقديمية إلى بايثون، بايثون للعروض التقديمية، Aspose.Slides بايثون، تحويل PPT إلى PNG، مكتبة بايثون التقديمية
description: تحويل PPT إلى PNG في بايثون. استخدم واجهة برمجة تطبيقات مكتبة Python لتحويل ملفات PPT إلى PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PPT إلى PNG بسهولة باستخدام Python: Aspose.Slides to the Rescue!" h2="أضف حياة جديدة إلى عروضك التقديمية باستخدام لغة بايثون. يرشدك دليلنا خلال تحويل شرائح PowerPoint الحالية إلى عروض تقديمية جذابة لـ Python." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PPT إلى PNG في بايثون" %}}

هل سئمت من المصارعة مع برامج العرض التقديمي المعقدة؟ لا تنظر أبعد من [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/ar/python-java/)! تمكّنك هذه المكتبة القوية من إنشاء العروض التقديمية وتحريرها وتحويلها بين التنسيقات المختلفة بسهولة. هل تحتاج إلى التبديل من PPT إلى PNG؟ يجعل Aspose.Slides الأمر أمرًا سهلاً، حيث يتطلب بضعة أسطر فقط من كود Python.

باعتبارها واجهة برمجة تطبيقات متطورة لمعالجة المستندات، تتميز **Aspose.Slides for Python عبر Java** بسرعات تحويل فائقة السرعة، مما يضمن التحويل السريع لعروضك التقديمية PPT إلى تنسيق PNG. تخلص من قيود الأدوات التقليدية - يمنحك Aspose.Slides المرونة اللازمة لتحويل العروض التقديمية من PPT إلى PNG ليس فقط ولكن أيضًا مجموعة واسعة من التنسيقات الأخرى، مما يمكّنك من تكييف عروضك التقديمية بشكل لا تشوبه شائبة مع أي موقف.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل PPT إلى PNG باستخدام Python" %}}
لتحويل PPT إلى PNG، ستحتاج إلى إنشاء عرض تقديمي من ملف PPT وحفظه باسم PNG.

{{% blocks/products/pf/agp/code-block title="برنامج تعليمي لبايثون لتحويل PPT إلى PNG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppt");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="دروس بايثون. كيفية تحويل PPT إلى PNG باستخدام Aspose.Slides لـ Python عبر Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="لتحويل PPT إلى PNG باستخدام Aspose.Slides لـ Python عبر Java، تحتاج إلى استيراد الحزمة إلى برنامج Python النصي الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [**Aspose.Slides for Python عبر Java**](https://products.aspose.com/slides/ar/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Python الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح ملفات المصدر PPT في Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل PPT إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PPT وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}