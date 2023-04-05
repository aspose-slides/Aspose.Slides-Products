---
title: Görüntüyü Java'da PDF ile Birleştirme
url: /tr/java/merger/image-to-pdf/
keywords: Görüntüyü PDF'ye Dönüştürme, Görüntüyü PDF'ye Birleştirme, Görüntüyü PDF'ye Birleştirme, PDF, Görüntü, Java API, Java Kitaplığı
description: Java'da Görüntüyü PDF'ye Birleştirme. Görüntü ve PDF'yi birleştirmek için Java kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Görüntüyü Java'da PDF ile Birleştirme" h2="Java kodunu kullanarak Görüntüyü PDF dosyalarıyla birleştirmek için yüksek hızlı ve platformlar arası Java kitaplığı" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak Görüntüyü PDF'ye Birleştirme" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), sunumlar, PDF'ler, resimler ve diğerlerini oluşturmak, dönüştürmek, birleştirmek ve değiştirmek için kullanılan güçlü bir Java kitaplığıdır. Dosyalar. Görüntüyü PDF'de birleştirdiğinizde, tek bir PDF dosyası elde etmek için görüntüleri etkili bir şekilde birleştirmiş olursunuz.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Görüntüyü Java'da PDF ile Birleştirme" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/) kullanarak, yalnızca birkaç satır kodla görüntüyü PDF'de hızla birleştirebilirsiniz

{{% blocks/products/pf/agp/code-block title="Görüntüyü PDF ile birleştirmek için Java kodu" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    pres.save("pres.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Görüntüyü Java'da PDF ile birleştirme" >}}


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
Birleştirmek istediğiniz görüntüleri resim çerçeveleri olarak yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan PDF'yi kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDF Dosyalarını Çevrimiçi Birleştirme" sectionDescription="[Python'da PDF Nasıl Birleştirilir](https://products.aspose.com/slides/tr/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları birleştir" subTitle="Tek bir dosya elde etmek için diğer formatlardaki dosyaları da birleştirebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}