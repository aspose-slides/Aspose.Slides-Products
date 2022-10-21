---
title: Python Kullanarak PPTX Dosyalarını HTML İle Birleştirin
url: /tr/python-net/merge/pptx-to-html/
keywords: PPTX'ı HTML ile birleştir, PPTX ile HTML'a katıl, PPTX'ı HTML ile birleştir, PowerPoint, Presentation, HTML, Python, Aspose
description: Python'da birden çok PPTX dosyasını birleştirin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python'da PPTX dosyalarını HTML ile birleştirin" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası Python API." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da PPTX öğesini HTML ile birleştir" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Python kitaplığıdır. Ayrıca, birden çok PPTX sunumunu birleştirmek için esnek yollar sağlar. Bir sunuyu diğeriyle birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunuda etkili bir şekilde birleştirirsiniz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenize olanak tanır. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile sunuları birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python kullanarak PPTX dosyalarını HTML ile birleştirin" %}}
PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{% blocks/products/pf/agp/code-block title="Birden çok PPTX dosyasını tek bir HTML dosyasına birleştirmek için Python kodu" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pptx") as pres1:
    with slides.Presentation("presentation2.pptx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.html", slides.export.SaveFormat.HTML5)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API kullanılarak PPTX ile HTML arasında nasıl birleştirilir" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, iki PPTX dosyasını birleştirme ve sonucu Python'da HTML olarak kaydetme adımlarıdır." >}}

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
Kaynak PPTX dosyalarını Python'da açın.
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX dosyalarını [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) yöntemini kullanarak birleştirin.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunumu kaydedin ve sonucu tek HTML dosyası olarak alın.
```
pres1.save("presentation.html", slides.export.SaveFormat.HTML5)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPTX öğesini Desteklenen Diğer Biçimlere Dışa Aktarın" subTitle="Ayrıca PPTX öğesini birleştirebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-ppt/" name="PPTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-pdf/" name="PPTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-png/" name="PPTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-bmp/" name="PPTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-jpg/" name="PPTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-fodp/" name="PPTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-gif/" name="PPTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-odp/" name="PPTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-otp/" name="PPTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-pot/" name="PPTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-potm/" name="PPTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-potx/" name="PPTX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-pps/" name="PPTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-ppsm/" name="PPTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-ppsx/" name="PPTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-pptm/" name="PPTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-svg/" name="PPTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-tiff/" name="PPTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/merge/pptx-to-xps/" name="PPTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}