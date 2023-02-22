---
title: تحويل الصورة إلى PPTX في Python
url: /ar/python-net/conversion/image-to-pptx/
keywords: صورة إلى PPTX ، تحويل الصورة إلى PPTX ، Python API ، مكتبة Python ، صورة ، PPTX
description: تحويل الصورة إلى PPTX في Python. استخدم واجهة برمجة تطبيقات مكتبة Python لتحويل ملفات الصور إلى ملفات PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل الصورة إلى PPTX في Python" h2="مكتبة Python عالية السرعة ومتعددة الأنظمة تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل الصورة إلى PPTX في Python" %}}

[** Aspose.Slides for Python عبر .NET **](https://products.aspose.com/slides/ar/python-net/) هي مكتبة Python قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل الصورة إلى PPTX. باستخدام ** Aspose.Slides for Python عبر .NET ** ، يمكن لأي مطور أو تطبيق تحويل الصورة إلى ملفات PPTX ببضعة أسطر من كود Python.

بصفتها واجهة برمجة تطبيقات حديثة لمعالجة المستندات ، تقوم Aspose.Slides for Python بتصدير ملفات الصور إلى تنسيقات ملفات PPTX بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل الصور إلى ملفات PDF والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل الصورة إلى PPTX باستخدام Python" %}}
لتحويل الصورة إلى PPTX ، ستحتاج إلى إنشاء عرض تقديمي من ملف صورة وحفظه بتنسيق PPTX.

{{% blocks/products/pf/agp/code-block title="كود Python لتحويل الصورة إلى PPTX" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.pptx", slides.export.SaveFormat.PPTX)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل الصورة إلى PPTX باستخدام Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل الصورة إلى PPTX في Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ثبّت [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ar/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع Python الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح ملفات الصور المصدر في بايثون.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل الصورة إلى تنسيقات أخرى مدعومة" subTitle="يمكنك أيضًا تحويل الصورة وحفظها في تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}