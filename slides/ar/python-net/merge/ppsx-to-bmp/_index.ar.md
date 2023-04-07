---
title: دمج ملفات PPSX إلى BMP باستخدام Python
url: /ar/python-net/merge/ppsx-to-bmp/
keywords: دمج PPSX إلى BMP ، انضم إلى PPSX إلى BMP ، ادمج PPSX إلى BMP ، PowerPoint ، Presentation ، BMP ، Python ، Aspose
description: دمج عدة ملفات PPSX في بايثون.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="دمج ملفات PPSX في BMP معًا في Python" h2="واجهة برمجة تطبيقات Python عالية السرعة ومتعددة المنصات والتي تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="دمج PPSX إلى BMP في بايثون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ar/python-net/) هي مكتبة Python قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة للجمع بين عدة عروض تقديمية PPSX. عندما تقوم بدمج عرض تقديمي بآخر ، فأنت تقوم بدمج شرائحها بشكل فعال في عرض تقديمي واحد للحصول على ملف واحد. Aspose.Slides يسمح لك بدمج عرضين تقديميين بطرق مختلفة. يمكنك دمج العروض التقديمية بجميع أشكالها وأنماطها ونصوصها وتنسيقاتها وتعليقاتها ورسومها المتحركة وما إلى ذلك دون الحاجة إلى القلق بشأن فقدان الجودة أو البيانات.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="دمج ملفات PPSX في BMP باستخدام Python" %}}
لدمج عروض PowerPoint التقديمية ، ستحتاج إلى استنساخ الشرائح من عرض تقديمي إلى آخر.

{{% blocks/products/pf/agp/code-block title="كود Python لدمج عدة PPSX في ملف واحد BMP" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.ppsx") as pres1:
    with slides.Presentation("presentation2.ppsx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية دمج PPSX في BMP باستخدام Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لدمج ملفين من PPSX وحفظ النتيجة باسم BMP في بايثون." >}}

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
افتح المصدر من ملفات PPSX في بايثون.
```
pres1 = slides.Presentation('pres1.ppsx')
pres2 = slides.Presentation('pres2.ppsx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
اجمع ملفات PPSX باستخدام طريقة [** add_clone **](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ العرض التقديمي واحصل على النتيجة كملف BMP واحد.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="دمج ملفات PDF على الإنترنت" sectionDescription="[كيفية دمج ملفات PDF في بايثون](https://products.aspose.com/slides/ar/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تصدير PPSX إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا دمج PPSX وحفظه في تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-pptx/" name="PPSX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-ppt/" name="PPSX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-pdf/" name="PPSX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-html/" name="PPSX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-png/" name="PPSX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-jpg/" name="PPSX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-fodp/" name="PPSX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-gif/" name="PPSX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-odp/" name="PPSX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-otp/" name="PPSX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-pot/" name="PPSX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-potm/" name="PPSX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-potx/" name="PPSX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-pps/" name="PPSX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-pptm/" name="PPSX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-svg/" name="PPSX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-tiff/" name="PPSX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/ppsx-to-xps/" name="PPSX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}