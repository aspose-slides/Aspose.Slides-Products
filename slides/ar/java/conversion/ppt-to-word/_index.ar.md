---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPT إلى Word في Java
url: /ar/java/conversion/ppt-to-word/
keywords: تحويل PPT إلى Word ، PPT إلى Word ، PPT إلى DOC ، PowerPoint إلى Word ، Java API ، مكتبة Java
description: تحويل PPT إلى Word في Java. استخدم Java Library API لتحويل PowerPoint إلى Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPT إلى Word في Java" h2="واجهة برمجة تطبيقات Java قوية ومتعددة المنصات لتحويل PowerPoint إلى Word باستخدام Java code بدون Microsoft PowerPoint أو Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى Word في Java" variant="code" %}}

يمكنك تحويل PPT إلى Word بسرعة باستخدام بضعة أسطر من التعليمات البرمجية

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود جافا لتحويل PowerPoint إلى Word" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى Word باستخدام Aspose.Slides و Aspose.Words" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) و [** Aspose.Words لجافا **](https://products.aspose.com/ Words / java /) هي مكتبات Java قوية تستخدم لمعالجة وتحويل عروض PowerPoint التقديمية ومستندات Word والملفات الأخرى. عندما تقوم بتحويل PowerPoint إلى Word ، فأنت تقوم بشكل أساسي بنقل محتويات شرائح العرض التقديمي إلى صفحات في مستند Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PPT إلى Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تثبيت ** Aspose.Slides for Java ** و ** Aspose.Words لجافا **{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي وفئة المستند.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل العرض التقديمي PPT الذي تريد تحويله إلى Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء صور ونصوص بناءً على محتويات الشرائح.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ مستند Word الناتج.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="محول مجاني على الإنترنت"
  description="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PowerPoint إلى ملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
