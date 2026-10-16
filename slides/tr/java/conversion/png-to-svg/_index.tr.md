---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java'da PNG biçimini SVG biçimine dönüştürün
url: /tr/java/conversion/png-to-svg/
keywords: PNG'tan SVG'a, PNG'tan SVG'a Dönüştürme, Java API, Java Kitaplığı, PNG, SVG
description: Java'da PNG öğesini SVG biçimine dönüştürün. PNG dosyalarını SVG dosyalarına dönüştürmek için Java kitaplığı API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java'da PNG biçimini SVG biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Java Kitaplığı." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java kullanarak PNG biçimini SVG biçimine dönüştürün" variant="code" %}}

PNG dosyasını SVG biçimine dönüştürmek için, PNG dosyasından Sunu oluşturmanız ve onu SVG olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PNG biçimini SVG biçimine dönüştürmek için Java kodu" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);

        FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
        try {
            slide.writeAsSvg(fileStream);
        } finally {
            fileStream.close();
        }
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java'da PNG biçimini SVG biçimine dönüştürün" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Java kitaplığıdır. Ayrıca, PNG biçimini SVG biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Java**'yı kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satırlık Java koduyla PNG dosyalarını SVG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Java, PNG dosyalarını hızlı bir şekilde SVG dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, PNG biçimini SVG biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for Java API kullanarak PNG biçimini SVG biçimine dönüştürme" intro="Bunlar, Java'da PNG biçimini SVG biçimine dönüştürme adımlarıdır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/) yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Java projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak PNG dosyalarını Java'da açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu SVG dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ücretsiz Çevrimiçi Dönüştürücü"
  description="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PNG biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca PNG dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
