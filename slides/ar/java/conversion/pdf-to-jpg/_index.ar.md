---
title: تحويل PDF إلى JPG في جافا
url: /ar/java/conversion/pdf-to-jpg/
keywords: PDF إلى JPG ، تحويل PDF إلى JPG ، واجهة برمجة تطبيقات جافا ، مكتبة جافا ، PDF ، JPG
description: تحويل PDF إلى JPG في جافا. استخدم Java Library API لتحويل ملفات PDF إلى JPG s
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PDF إلى JPG في جافا" h2="مكتبة Java عالية السرعة ومتعددة الأنظمة تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PDF إلى JPG في جافا" %}}

تعد [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) مكتبة جافا قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل PDF إلى JPG. باستخدام ** Aspose.Slides for Java ** ، يمكن لأي مطور أو تطبيق تحويل PDF إلى JPG من الملفات ببضعة سطور من كود جافا.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، تصدر Aspose.Slides for Java ملفات PDF إلى JPG تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل PDF إلى JPG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل PDF إلى JPG باستخدام جافا" %}}
لتحويل PDF إلى JPG ، ستحتاج إلى إنشاء عرض تقديمي من ملف PDF وحفظه بتنسيق JPG.

{{% blocks/products/pf/agp/code-block title="كود جافا لتحويل PDF إلى JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    pres.getSlides().addFromPdf("InputPDF.pdf");
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PDF إلى JPG باستخدام Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل PDF إلى JPG في جافا." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع Java الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح المصدر من ملفات PDF بجافا.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل PDF إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PDF وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}