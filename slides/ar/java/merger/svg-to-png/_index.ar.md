---
title: دمج SVG في PNG في جافا
url: /ar/java/merger/svg-to-png/
keywords: دمج SVG في PNG ، و SVG إلى PNG ، والانضمام إلى SVG إلى PNG ، والجمع بين SVG و PNG ، و Java API ، و Java Library
description: دمج SVG في PNG في جافا. استخدم Java Library API لدمج ملفات SVG و PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="دمج SVG في PNG في جافا" h2="مكتبة Java عالية السرعة ومتعددة المنصات لدمج صور SVG إلى PNG باستخدام كود Java" >}}

{{% blocks/products/pf/feature-page-section h2="ادمج SVG في PNG باستخدام Aspose.Slides" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) هي مكتبة Java قوية تُستخدم لدمج ومعالجة العروض التقديمية والصور والملفات الأخرى. عندما تقوم بدمج SVG مع PNG ، فإنك تدمج صور SVG بشكل فعال للحصول على صورة PNG.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="دمج SVG في PNG في جافا" %}}
باستخدام [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) ، يمكنك دمج ملفات SVG مع ملفات PNG بسرعة باستخدام بضعة أسطر من التعليمات البرمجية

{{% blocks/products/pf/agp/code-block title="كود جافا لدمج SVG في PNG" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes("image.svg"));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage ppImage = pres.getImages().addImage(svgImage);
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 
			ppImage.getWidth(), ppImage.getHeight(), ppImage);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية دمج SVG في PNG في Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت ** Aspose.Slides for Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف المكتبة كمرجع في مشروعك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل ملفات SVG التي تريد دمجها معًا.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ صورة PNG الناتجة.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="دمج الملفات الأخرى" subTitle="يمكنك أيضًا دمج الملفات بتنسيقات أخرى للحصول على ملف واحد" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}