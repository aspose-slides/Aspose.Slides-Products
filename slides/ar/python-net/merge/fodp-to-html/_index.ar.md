---
title: دمج ملفات FODP إلى HTML باستخدام Python
url: /ar/python-net/merge/fodp-to-html/
keywords: دمج FODP إلى HTML ، انضم إلى FODP إلى HTML ، ادمج FODP إلى HTML ، PowerPoint ، Presentation ، HTML ، Python ، Aspose
description: دمج عدة ملفات FODP في بايثون.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="دمج ملفات FODP في HTML معًا في Python" h2="واجهة برمجة تطبيقات Python عالية السرعة ومتعددة المنصات والتي تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="دمج FODP إلى HTML في بايثون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ar/python-net/) هي مكتبة Python قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة للجمع بين عدة عروض تقديمية FODP. عندما تقوم بدمج عرض تقديمي بآخر ، فأنت تقوم بدمج شرائحها بشكل فعال في عرض تقديمي واحد للحصول على ملف واحد. Aspose.Slides يسمح لك بدمج عرضين تقديميين بطرق مختلفة. يمكنك دمج العروض التقديمية بجميع أشكالها وأنماطها ونصوصها وتنسيقاتها وتعليقاتها ورسومها المتحركة وما إلى ذلك دون الحاجة إلى القلق بشأن فقدان الجودة أو البيانات.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="دمج ملفات FODP في HTML باستخدام Python" %}}
لدمج عروض PowerPoint التقديمية ، ستحتاج إلى استنساخ الشرائح من عرض تقديمي إلى آخر.

{{% blocks/products/pf/agp/code-block title="كود Python لدمج عدة FODP في ملف واحد HTML" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.fodp") as pres1:
    with slides.Presentation("presentation2.fodp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.html", slides.export.SaveFormat.HTML5)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية دمج FODP في HTML باستخدام Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لدمج ملفين من FODP وحفظ النتيجة باسم HTML في بايثون." >}}

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
افتح المصدر من ملفات FODP في بايثون.
```
pres1 = slides.Presentation('pres1.fodp')
pres2 = slides.Presentation('pres2.fodp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
اجمع ملفات FODP باستخدام طريقة [** add_clone **](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ العرض التقديمي واحصل على النتيجة كملف HTML واحد.
```
pres1.save("presentation.html", slides.export.SaveFormat.HTML5)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="دمج ملفات PDF على الإنترنت" sectionDescription="[كيفية دمج ملفات PDF في بايثون](https://products.aspose.com/slides/ar/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تصدير FODP إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا دمج FODP وحفظه في تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-pptx/" name="FODP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-ppt/" name="FODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-pdf/" name="FODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-png/" name="FODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-bmp/" name="FODP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-jpg/" name="FODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-gif/" name="FODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-odp/" name="FODP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-otp/" name="FODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-pot/" name="FODP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-potm/" name="FODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-potx/" name="FODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-pps/" name="FODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-ppsm/" name="FODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-ppsx/" name="FODP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-pptm/" name="FODP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-svg/" name="FODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-tiff/" name="FODP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/merge/fodp-to-xps/" name="FODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}