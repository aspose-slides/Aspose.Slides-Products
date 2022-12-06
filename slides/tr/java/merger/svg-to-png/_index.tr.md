---
title: Java'da SVG'yi PNG ile birleştirme
url: /tr/java/merger/svg-to-png/
keywords: SVG'yi PNG'ye Birleştirme, SVG'yi PNG'ye Birleştirme, SVG'yi PNG'ye Birleştirme, SVG'yi PNG'ye Birleştirme, Java API, Java Kitaplığı
description: Java'da SVG'yi PNG ile birleştirin. SVG ve PNG dosyalarını birleştirmek için Java kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java'da SVG'yi PNG ile birleştirme" h2="Java kodunu kullanarak SVG'yi PNG görüntüleri ile birleştirmek için yüksek hızlı ve platformlar arası Java kitaplığı" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak SVG'yi PNG ile birleştirin" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), sunumları, resimleri ve diğer dosyaları birleştirmek ve değiştirmek için kullanılan güçlü bir Java kitaplığıdır. SVG'yi PNG ile birleştirdiğinizde, bir PNG resmi elde etmek için SVG resimlerini etkili bir şekilde birleştirmiş olursunuz.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Java'da SVG'yi PNG ile birleştirme" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/) kullanarak, yalnızca birkaç satır kodla SVG'yi PNG dosyalarına hızla birleştirebilirsiniz

{{% blocks/products/pf/agp/code-block title="SVG'yi PNG ile birleştirmek için Java kodu" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Java'da SVG'yi PNG ile birleştirme" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java**'yı kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Birlikte birleştirmek istediğiniz SVG dosyalarını yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan PNG görüntüsünü kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları birleştir" subTitle="Tek bir dosya elde etmek için diğer formatlardaki dosyaları da birleştirebilirsiniz." >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}