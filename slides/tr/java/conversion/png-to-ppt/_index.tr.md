---
title: PNG'yi Java'da PPT'ye dönüştürün
url: /tr/java/conversion/png-to-ppt/
keywords: PNG'yi PPT'ye, PNG'yi PPT'ye, PowerPoint'e, PNG'ye, PPT'ye, Java API'sine, Java Kitaplığına dönüştürün
description: PNG'yi Java'da PPT'ye dönüştürün. PNG resimlerini PowerPoint'e dönüştürmek için Java kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PNG'yi Java'da PPT'ye dönüştürün" h2="Java kodunu kullanarak PNG'yi PPT'ye dönüştürmek için güçlü platformlar arası Java API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak PNG'yi PPT'ye dönüştürün" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), PowerPoint sunumları, PDF'ler, HTML belgeleri ve diğerlerini oluşturmak, dönüştürmek ve değiştirmek için kullanılan güçlü bir Java kitaplığıdır. Dosyalar. PNG'yi PPT'ye dönüştürdüğünüzde, aslında PNG görüntülerine dayalı slaytlar içeren bir PowerPoint sunusu oluşturmuş olursunuz.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="PNG'yi Java'da PPT'ye dönüştürün" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/) kullanarak PNG görüntüsünü birkaç satır kodla PowerPoint sunumuna dönüştürebilirsiniz:

{{% blocks/products/pf/agp/code-block title="PNG'yi PPT'ye dönüştürmek için Java kodu" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Java'da PNG'yi PPT'ye dönüştürme" >}}


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
PPT'ye dönüştürmek istediğiniz PNG görüntüsünü yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan dosyayı bir PPT sunumu olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen PowerPoint Dönüşümleri" subTitle="Diğer biçimlerdeki dosyaları da PowerPoint'e dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}