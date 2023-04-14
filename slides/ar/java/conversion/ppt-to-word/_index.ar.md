---
title: تحويل PPT إلى Word في Java
url: /ar/java/conversion/ppt-to-word/
keywords: تحويل PPT إلى Word ، PPT إلى Word ، PPT إلى DOC ، PowerPoint إلى Word ، Java API ، مكتبة Java
description: تحويل PPT إلى Word في Java. استخدم Java Library API لتحويل PowerPoint إلى Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PPT إلى Word في Java" h2="واجهة برمجة تطبيقات Java قوية ومتعددة المنصات لتحويل PowerPoint إلى Word باستخدام Java code بدون Microsoft PowerPoint أو Office" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PowerPoint إلى Word باستخدام Aspose.Slides و Aspose.Words" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) و [** Aspose.Words لجافا **](https://products.aspose.com/ Words / java /) هي مكتبات Java قوية تستخدم لمعالجة وتحويل عروض PowerPoint التقديمية ومستندات Word والملفات الأخرى. عندما تقوم بتحويل PowerPoint إلى Word ، فأنت تقوم بشكل أساسي بنقل محتويات شرائح العرض التقديمي إلى صفحات في مستند Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="تحويل PowerPoint إلى Word في Java" %}}
يمكنك تحويل PPT إلى Word بسرعة باستخدام بضعة أسطر من التعليمات البرمجية

{{% blocks/products/pf/agp/code-block title="كود جافا لتحويل PowerPoint إلى Word" offSpacer="true" %}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PPT إلى Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
تثبيت ** Aspose.Slides for Java ** و ** Aspose.Words لجافا ** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي وفئة المستند.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل العرض التقديمي PPT الذي تريد تحويله إلى Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء صور ونصوص بناءً على محتويات الشرائح.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ مستند Word الناتج.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PowerPoint إلى ملفات بتنسيقات أخرى" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}