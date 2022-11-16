---
title: Java'da PNG biçimini PDF biçimine dönüştürün
url: /tr/java/conversion/png-to-pdf/
keywords: PNG'tan PDF'a, PNG'tan PDF'a Dönüştürme, Java API, Java Kitaplığı, PNG, PDF
description: Java'da PNG öğesini PDF biçimine dönüştürün. PNG dosyalarını PDF dosyalarına dönüştürmek için Java kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java'da PNG biçimini PDF biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Java Kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="Java'da PNG biçimini PDF biçimine dönüştürün" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Java kitaplığıdır. Ayrıca, PNG biçimini PDF biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Java**'yı kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satırlık Java koduyla PNG dosyalarını PDF dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Java, PNG dosyalarını hızlı bir şekilde PDF dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, PNG biçimini PDF biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java kullanarak PNG biçimini PDF biçimine dönüştürün" %}}
PNG dosyasını PDF biçimine dönüştürmek için, PNG dosyasından Sunu oluşturmanız ve onu PDF olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PNG biçimini PDF biçimine dönüştürmek için Java kodu" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Java API kullanarak PNG biçimini PDF biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, Java'da PNG biçimini PDF biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source PNG files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PDF file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PNG biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca PNG dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}