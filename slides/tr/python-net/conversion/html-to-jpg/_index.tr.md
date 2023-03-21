---
title: Python'da HTML öğesini JPG biçimine dönüştürün
url: /tr/python-net/conversion/html-to-jpg/
keywords: HTML'tan JPG'a, HTML'tan JPG'a Dönüştürme, Python API, Python Kitaplığı, HTML, JPG
description: Python'da HTML öğesini JPG biçimine dönüştürün. HTML dosyalarını JPG dosyalarına dönüştürmek için Python kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python'da HTML öğesini JPG biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Python Kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da HTML öğesini JPG biçimine dönüştürün" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Python kitaplığıdır. Ayrıca, HTML biçimini JPG biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Python via .NET** ile herhangi bir geliştirici veya uygulama, yalnızca birkaç satırlık Python koduyla HTML dosyalarını JPG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Python, HTML dosyalarını hızlı bir şekilde JPG dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, HTML biçimini JPG biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python kullanarak HTML biçimini JPG biçimine dönüştürün" %}}
HTML dosyasını JPG biçimine dönüştürmek için, HTML dosyasından Sunu oluşturmanız ve onu JPG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="HTML biçimini JPG biçimine dönüştürmek için Python kodu" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open(dataDir + "file.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.jpeg)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API kullanarak HTML biçimini JPG biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, Python'da HTML biçimini JPG biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak HTML dosyalarını Python'da açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu JPG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="HTML biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca HTML dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}