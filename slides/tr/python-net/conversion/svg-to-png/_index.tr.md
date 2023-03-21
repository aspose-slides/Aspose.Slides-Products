---
title: Python'da SVG öğesini PNG biçimine dönüştürün
url: /tr/python-net/conversion/svg-to-png/
keywords: SVG'tan PNG'a, SVG'tan PNG'a Dönüştürme, Python API, Python Kitaplığı, SVG, PNG
description: Python'da SVG öğesini PNG biçimine dönüştürün. SVG dosyalarını PNG dosyalarına dönüştürmek için Python kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python'da SVG öğesini PNG biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Python Kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da SVG öğesini PNG biçimine dönüştürün" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Python kitaplığıdır. Ayrıca, SVG biçimini PNG biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Python via .NET** ile herhangi bir geliştirici veya uygulama, yalnızca birkaç satırlık Python koduyla SVG dosyalarını PNG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Python, SVG dosyalarını hızlı bir şekilde PNG dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, SVG biçimini PNG biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python kullanarak SVG biçimini PNG biçimine dönüştürün" %}}
SVG dosyasını PNG biçimine dönüştürmek için, SVG dosyasından Sunu oluşturmanız ve onu PNG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="SVG biçimini PNG biçimine dönüştürmek için Python kodu" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API kullanarak SVG biçimini PNG biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, Python'da SVG biçimini PNG biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak SVG dosyalarını Python'da açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PNG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="SVG biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca SVG dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}