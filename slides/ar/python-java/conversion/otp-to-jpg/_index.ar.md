---
title: تحويل OTP إلى JPG في بايثون
url: /ar/python-java/conversion/otp-to-jpg/
keywords: تحويل العروض التقديمية بايثون، تحويل العروض التقديمية إلى بايثون، بايثون للعروض التقديمية، Aspose.Slides بايثون، تحويل OTP إلى JPG، مكتبة بايثون التقديمية
description: تحويل OTP إلى JPG في بايثون. استخدم واجهة برمجة تطبيقات مكتبة Python لتحويل ملفات OTP إلى JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل OTP إلى JPG بسهولة باستخدام Python: Aspose.Slides to the Rescue!" h2="أضف حياة جديدة إلى عروضك التقديمية باستخدام لغة بايثون. يرشدك دليلنا خلال تحويل شرائح PowerPoint الحالية إلى عروض تقديمية جذابة لـ Python." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل OTP إلى JPG في بايثون" %}}

هل سئمت من المصارعة مع برامج العرض التقديمي المعقدة؟ لا تنظر أبعد من [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/ar/python-java/)! تمكّنك هذه المكتبة القوية من إنشاء العروض التقديمية وتحريرها وتحويلها بين التنسيقات المختلفة بسهولة. هل تحتاج إلى التبديل من OTP إلى JPG؟ يجعل Aspose.Slides الأمر أمرًا سهلاً، حيث يتطلب بضعة أسطر فقط من كود Python.

باعتبارها واجهة برمجة تطبيقات متطورة لمعالجة المستندات، تتميز **Aspose.Slides for Python عبر Java** بسرعات تحويل فائقة السرعة، مما يضمن التحويل السريع لعروضك التقديمية OTP إلى تنسيق JPG. تخلص من قيود الأدوات التقليدية - يمنحك Aspose.Slides المرونة اللازمة لتحويل العروض التقديمية من OTP إلى JPG ليس فقط ولكن أيضًا مجموعة واسعة من التنسيقات الأخرى، مما يمكّنك من تكييف عروضك التقديمية بشكل لا تشوبه شائبة مع أي موقف.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل OTP إلى JPG باستخدام Python" %}}
لتحويل OTP إلى JPG، ستحتاج إلى إنشاء عرض تقديمي من ملف OTP وحفظه باسم JPG.

{{% blocks/products/pf/agp/code-block title="برنامج تعليمي لبايثون لتحويل OTP إلى JPG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.otp");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="دروس بايثون. كيفية تحويل OTP إلى JPG باستخدام Aspose.Slides لـ Python عبر Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="لتحويل OTP إلى JPG باستخدام Aspose.Slides لـ Python عبر Java، تحتاج إلى استيراد الحزمة إلى برنامج Python النصي الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [**Aspose.Slides for Python عبر Java**](https://products.aspose.com/slides/ar/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Python الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح ملفات المصدر OTP في Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل OTP إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل OTP وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-java/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}