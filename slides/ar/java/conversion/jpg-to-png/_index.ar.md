---
title: تحويل JPG إلى PNG في جافا
url: /ar/java/conversion/jpg-to-png/
keywords: JPG إلى PNG ، تحويل JPG إلى PNG ، واجهة برمجة تطبيقات جافا ، مكتبة جافا ، JPG ، PNG
description: تحويل JPG إلى PNG في جافا. استخدم Java Library API لتحويل ملفات JPG إلى PNG s
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل JPG إلى PNG في جافا" h2="مكتبة Java عالية السرعة ومتعددة الأنظمة تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل JPG إلى PNG في جافا" %}}

تعد [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) مكتبة جافا قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل JPG إلى PNG. باستخدام ** Aspose.Slides for Java ** ، يمكن لأي مطور أو تطبيق تحويل JPG إلى PNG من الملفات ببضعة سطور من كود جافا.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، تصدر Aspose.Slides for Java ملفات JPG إلى PNG تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل JPG إلى PNG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل JPG إلى PNG باستخدام جافا" %}}
لتحويل JPG إلى PNG ، ستحتاج إلى إنشاء عرض تقديمي من ملف JPG وحفظه بتنسيق PNG.

{{% blocks/products/pf/agp/code-block title="كود جافا لتحويل JPG إلى PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل JPG إلى PNG باستخدام Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل JPG إلى PNG في جافا." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع Java الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح المصدر من ملفات JPG بجافا.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل JPG إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل JPG وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}