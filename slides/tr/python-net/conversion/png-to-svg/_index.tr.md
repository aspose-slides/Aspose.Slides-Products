---
title: Python'da PNG öğesini SVG biçimine dönüştürün
url: /tr/python-net/conversion/png-to-svg/
keywords: PNG'tan SVG'a, PNG'tan SVG'a Dönüştürme, Python API, Python Kitaplığı, PNG, SVG
description: Python'da PNG öğesini SVG biçimine dönüştürün. PNG dosyalarını SVG dosyalarına dönüştürmek için Python kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python'da PNG öğesini SVG biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Python Kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da PNG öğesini SVG biçimine dönüştürün" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Python kitaplığıdır. Ayrıca, PNG biçimini SVG biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Python via .NET** ile herhangi bir geliştirici veya uygulama, yalnızca birkaç satırlık Python koduyla PNG dosyalarını SVG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Python, PNG dosyalarını hızlı bir şekilde SVG dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, PNG biçimini SVG biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python kullanarak PNG biçimini SVG biçimine dönüştürün" %}}
PNG dosyasını SVG biçimine dönüştürmek için, PNG dosyasından Sunu oluşturmanız ve onu SVG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PNG biçimini SVG biçimine dönüştürmek için Python kodu" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API kullanarak PNG biçimini SVG biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, Python'da PNG biçimini SVG biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PNG dosyalarını Python'da açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu SVG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="PNG biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca PNG dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}