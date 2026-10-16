---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PDF إلى JPG في بايثون
url: /ar/python-java/conversion/pdf-to-jpg/
keywords: تحويل العروض التقديمية بايثون، تحويل العروض التقديمية إلى بايثون، بايثون للعروض التقديمية، Aspose.Slides بايثون، تحويل PDF إلى JPG، مكتبة بايثون التقديمية
description: تحويل PDF إلى JPG في بايثون. استخدم واجهة برمجة تطبيقات مكتبة Python لتحويل ملفات PDF إلى JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PDF إلى JPG بسهولة باستخدام Python: Aspose.Slides to the Rescue!" h2="أضف حياة جديدة إلى عروضك التقديمية باستخدام لغة بايثون. يرشدك دليلنا خلال تحويل شرائح PowerPoint الحالية إلى عروض تقديمية جذابة لـ Python." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PDF إلى JPG باستخدام Python" variant="code" %}}

لتحويل PDF إلى JPG، ستحتاج إلى إنشاء عرض تقديمي من ملف PDF وحفظه باسم JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="برنامج تعليمي لبايثون لتحويل PDF إلى JPG" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PDF إلى JPG في بايثون" %}}

هل سئمت من المصارعة مع برامج العرض التقديمي المعقدة؟ لا تنظر أبعد من [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/ar/python-java/)! تمكّنك هذه المكتبة القوية من إنشاء العروض التقديمية وتحريرها وتحويلها بين التنسيقات المختلفة بسهولة. هل تحتاج إلى التبديل من PDF إلى JPG؟ يجعل Aspose.Slides الأمر أمرًا سهلاً، حيث يتطلب بضعة أسطر فقط من كود Python.

باعتبارها واجهة برمجة تطبيقات متطورة لمعالجة المستندات، تتميز **Aspose.Slides for Python عبر Java** بسرعات تحويل فائقة السرعة، مما يضمن التحويل السريع لعروضك التقديمية PDF إلى تنسيق JPG. تخلص من قيود الأدوات التقليدية - يمنحك Aspose.Slides المرونة اللازمة لتحويل العروض التقديمية من PDF إلى JPG ليس فقط ولكن أيضًا مجموعة واسعة من التنسيقات الأخرى، مما يمكّنك من تكييف عروضك التقديمية بشكل لا تشوبه شائبة مع أي موقف.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="دروس بايثون. كيفية تحويل PDF إلى JPG باستخدام Aspose.Slides لـ Python عبر Java API." intro="لتحويل PDF إلى JPG باستخدام Aspose.Slides لـ Python عبر Java، تحتاج إلى استيراد الحزمة إلى برنامج Python النصي الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت [**Aspose.Slides for Python عبر Java**](https://products.aspose.com/slides/ar/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Python الخاص بك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملفات المصدر PDF في Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حفظ النتيجة كملف JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويل PDF إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PDF وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
