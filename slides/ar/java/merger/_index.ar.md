---
title: دمج PDF و PPT و PPTX والعديد من تنسيقات الملفات الأخرى باستخدام Java
url: /ar/java/merger/
keywords: دمج ، انضمام ، PowerPoint ، عرض تقديمي ، جافا ، Aspose
description: دمج ملفات متعددة في Java PPT و PPTX و ODP و PDF و PNG و JPG وغيرها الكثير.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ادمج Powerpoint أو PDF أو PPT أو المستندات الأخرى معًا في Java" h2="مكتبة Java عالية السرعة لدمج تنسيقات PPT و PPTX و PDF و PNG و JPEG وغيرها." >}}

{{% blocks/products/pf/feature-page-section h2="دمج PPT ، PPTX ، PDF باستخدام Java" %}}

تعد [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) مكتبة جافا قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة للجمع بين عروض تقديمية متعددة PPT / PPTX. عندما تقوم بدمج عرض تقديمي بآخر ، فأنت تقوم بدمج شرائحها بشكل فعال في عرض تقديمي واحد للحصول على ملف واحد. Aspose.Slides يسمح لك بدمج عرضين تقديميين بطرق مختلفة. يمكنك دمج العروض التقديمية بجميع أشكالها وأنماطها ونصوصها وتنسيقاتها وتعليقاتها ورسومها المتحركة وما إلى ذلك دون الحاجة إلى القلق بشأن فقدان الجودة أو البيانات.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="دمج عروض PowerPoint التقديمية في Java" %}}
لدمج عروض PowerPoint التقديمية ، ستحتاج إلى استنساخ الشرائح من عرض تقديمي إلى آخر.

{{% blocks/products/pf/agp/code-block title="دمج ملفات PPTX باستخدام Java" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="دمج العروض التقديمية مع Slide Master باستخدام Java" %}}
يوضح كود Java هذا كيفية دمج العديد من العروض التقديمية في واحد وتطبيق الأنماط من قالب العرض التقديمي للشريحة الرئيسية. لذلك ، سيحتفظ عرض النتيجة بنفس تنسيق المصدر وسيحتوي على تنسيق من شريحة رئيسية لعرض تقديمي آخر.

{{% blocks/products/pf/agp/code-block title="دمج عدة PPT في واحد في Java" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية دمج العروض التقديمية باستخدام Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لدمج ملفي PPTX وحفظ النتيجة بتنسيق PDF في Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [** Aspose.Slides for Java **](https://docs.aspose.com/slides/java/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع Java الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح ملفات PPTX المصدر في Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ادمج ملفات PPTX باستخدام طريقة ** addClone **.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ العرض التقديمي واحصل على النتيجة كملف PDF واحد.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات أخرى مدعومة لدمجها" subTitle="يمكنك أيضًا دمج تنسيقات ملفات أخرى. انظر التنسيقات الأخرى المدعومة أدناه." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}