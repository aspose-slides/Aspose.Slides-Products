---
title: Python'da PNG'yi PPTX'e dönüştürme
url: /tr/python-net/conversion/png-to-pptx/
keywords: PNG'yi PPTX'e, PNG'yi PPTX'e, PowerPoint'e, PNG'ye, PPTX'e, Python API'sine, Python Kitaplığına dönüştürün
description: PNG'yi Python'da PPTX'e dönüştürün. PNG resimlerini PowerPoint'e dönüştürmek için Python kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python'da PNG'yi PPTX'e dönüştürme" h2="Python kodunu kullanarak PNG'yi PPTX'e dönüştürmek için güçlü çapraz platform Python API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak PNG'yi PPTX'e dönüştürün" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/), PowerPoint sunuları, PDF'ler oluşturmak, dönüştürmek ve değiştirmek için kullanılan güçlü bir Python kitaplığıdır. HTML belgeleri ve diğer dosyalar. PNG'yi PPTX'e dönüştürdüğünüzde, aslında PNG görüntülerini temel alan slaytlar içeren bir PowerPoint sunusu oluşturmuş olursunuz.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Python'da PNG'yi PPTX'e dönüştürme" %}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) kullanarak PNG görüntüsünü yalnızca birkaç satır kodla PowerPoint sunumuna dönüştürebilirsiniz:

{{% blocks/products/pf/agp/code-block title="PNG'yi PPTX'e dönüştürmek için Python kodu" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Python'da PNG'yi PPTX'e dönüştürme" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Python'u .NET üzerinden** kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX'e dönüştürmek istediğiniz PNG görüntüsünü yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan dosyayı bir PPTX sunumu olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen PowerPoint Dönüşümleri" subTitle="Diğer biçimlerdeki dosyaları da PowerPoint'e dönüştürebilirsiniz." >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}