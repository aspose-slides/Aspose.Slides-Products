---
title: Python Kullanarak FODP Dosyalarını PPSX İle Birleştirin
url: /tr/python-net/merge/fodp-to-ppsx/
keywords: FODP'ı PPSX ile birleştir, FODP ile PPSX'a katıl, FODP'ı PPSX ile birleştir, PowerPoint, Presentation, PPSX, Python, Aspose
description: Python'da birden çok FODP dosyasını birleştirin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python'da FODP dosyalarını PPSX ile birleştirin" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Python API." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da FODP öğesini PPSX ile birleştir" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Python kitaplığıdır. Ayrıca, birden çok FODP sunumunu birleştirmek için esnek yollar sağlar. Bir sunuyu diğeriyle birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunuda etkili bir şekilde birleştirirsiniz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenize olanak tanır. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile sunuları birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python kullanarak FODP dosyalarını PPSX ile birleştirin" %}}
PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{% blocks/products/pf/agp/code-block title="Birden çok FODP dosyasını tek bir PPSX dosyasına birleştirmek için Python kodu" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.fodp") as pres1:
    with slides.Presentation("presentation2.fodp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.ppsx", slides.export.SaveFormat.PPSX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API kullanılarak FODP ile PPSX arasında nasıl birleştirilir" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, iki FODP dosyasını birleştirme ve sonucu Python'da PPSX olarak kaydetme adımlarıdır." >}}

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
Kaynak FODP dosyalarını Python'da açın.
```
pres1 = slides.Presentation('pres1.fodp')
pres2 = slides.Presentation('pres2.fodp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
FODP dosyalarını [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) yöntemini kullanarak birleştirin.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunumu kaydedin ve sonucu tek PPSX dosyası olarak alın.
```
pres1.save("presentation.ppsx", slides.export.SaveFormat.PPSX)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="FODP öğesini Desteklenen Diğer Biçimlere Dışa Aktarın" subTitle="Ayrıca FODP öğesini birleştirebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-pptx/" name="FODP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-ppt/" name="FODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-pdf/" name="FODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-html/" name="FODP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-png/" name="FODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-bmp/" name="FODP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-jpg/" name="FODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-gif/" name="FODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-odp/" name="FODP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-otp/" name="FODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-pot/" name="FODP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-potm/" name="FODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-potx/" name="FODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-pps/" name="FODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-ppsm/" name="FODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-pptm/" name="FODP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-svg/" name="FODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-tiff/" name="FODP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/fodp-to-xps/" name="FODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}