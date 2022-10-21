---
title: دمج ملفات PPT إلى SVG باستخدام Python
url: /ar/python-net/merge/ppt-to-svg/
keywords: دمج PPT إلى SVG ، انضم إلى PPT إلى SVG ، ادمج PPT إلى SVG ، PowerPoint ، Presentation ، SVG ، Python ، Aspose
description: دمج عدة ملفات PPT في بايثون.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="دمج ملفات PPT في SVG معًا في Python" h2="واجهة برمجة تطبيقات Python عالية السرعة ومتعددة المنصات والتي تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="دمج PPT إلى SVG في بايثون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ar/python-net/) هي مكتبة Python قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة للجمع بين عدة عروض تقديمية PPT. عندما تقوم بدمج عرض تقديمي بآخر ، فأنت تقوم بدمج شرائحها بشكل فعال في عرض تقديمي واحد للحصول على ملف واحد. Aspose.Slides يسمح لك بدمج عرضين تقديميين بطرق مختلفة. يمكنك دمج العروض التقديمية بجميع أشكالها وأنماطها ونصوصها وتنسيقاتها وتعليقاتها ورسومها المتحركة وما إلى ذلك دون الحاجة إلى القلق بشأن فقدان الجودة أو البيانات.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="دمج ملفات PPT في SVG باستخدام Python" %}}
لدمج عروض PowerPoint التقديمية ، ستحتاج إلى استنساخ الشرائح من عرض تقديمي إلى آخر.

{{% blocks/products/pf/agp/code-block title="كود Python لدمج عدة PPT في ملف واحد SVG" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.ppt") as pres1:
    with slides.Presentation("presentation2.ppt") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية دمج PPT في SVG باستخدام Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لدمج ملفين من PPT وحفظ النتيجة باسم SVG في بايثون." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ثبّت [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ar/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع Python الخاص بك.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح المصدر من ملفات PPT في بايثون.
```
pres1 = slides.Presentation('pres1.ppt')
pres2 = slides.Presentation('pres2.ppt')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
اجمع ملفات PPT باستخدام طريقة [** add_clone **](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ العرض التقديمي واحصل على النتيجة كملف SVG واحد.
```
for slide in pres1.slides:
    with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
        slide.write_as_svg(file)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تصدير PPT إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا دمج PPT وحفظه في تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-pptx/" name="PPT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-pdf/" name="PPT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-html/" name="PPT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-png/" name="PPT TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-bmp/" name="PPT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-jpg/" name="PPT TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-fodp/" name="PPT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-gif/" name="PPT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-odp/" name="PPT TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-otp/" name="PPT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-pot/" name="PPT TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-potm/" name="PPT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-potx/" name="PPT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-pps/" name="PPT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-ppsm/" name="PPT TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-ppsx/" name="PPT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-pptm/" name="PPT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-tiff/" name="PPT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppt-to-xps/" name="PPT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}