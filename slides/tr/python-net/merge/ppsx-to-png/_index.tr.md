---
title: Python Kullanarak PPSX Dosyalarını PNG İle Birleştirin
url: /tr/python-net/merge/ppsx-to-png/
keywords: PPSX'ı PNG ile birleştir, PPSX ile PNG'a katıl, PPSX'ı PNG ile birleştir, PowerPoint, Presentation, PNG, Python, Aspose
description: Python'da birden çok PPSX dosyasını birleştirin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python'da PPSX dosyalarını PNG ile birleştirin" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Python API." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da PPSX öğesini PNG ile birleştir" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Python kitaplığıdır. Ayrıca, birden çok PPSX sunumunu birleştirmek için esnek yollar sağlar. Bir sunuyu diğeriyle birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunuda etkili bir şekilde birleştirirsiniz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenize olanak tanır. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile sunuları birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python kullanarak PPSX dosyalarını PNG ile birleştirin" %}}
PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{% blocks/products/pf/agp/code-block title="Birden çok PPSX dosyasını tek bir PNG dosyasına birleştirmek için Python kodu" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.ppsx") as pres1:
    with slides.Presentation("presentation2.ppsx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API kullanılarak PPSX ile PNG arasında nasıl birleştirilir" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, iki PPSX dosyasını birleştirme ve sonucu Python'da PNG olarak kaydetme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) yükleyin.
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PPSX dosyalarını Python'da açın.
```
pres1 = slides.Presentation('pres1.ppsx')
pres2 = slides.Presentation('pres2.ppsx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPSX dosyalarını [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) yöntemini kullanarak birleştirin.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunumu kaydedin ve sonucu tek PNG dosyası olarak alın.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPSX öğesini Desteklenen Diğer Biçimlere Dışa Aktarın" subTitle="Ayrıca PPSX öğesini birleştirebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-pptx/" name="PPSX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-ppt/" name="PPSX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-pdf/" name="PPSX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-html/" name="PPSX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-bmp/" name="PPSX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-jpg/" name="PPSX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-fodp/" name="PPSX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-gif/" name="PPSX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-odp/" name="PPSX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-otp/" name="PPSX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-pot/" name="PPSX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-potm/" name="PPSX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-potx/" name="PPSX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-pps/" name="PPSX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-pptm/" name="PPSX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-svg/" name="PPSX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-tiff/" name="PPSX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/ppsx-to-xps/" name="PPSX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}