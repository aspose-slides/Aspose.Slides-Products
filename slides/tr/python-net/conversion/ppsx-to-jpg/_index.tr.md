---
title: Python'da PPSX'i JPG'ye Dönüştür
weight: 2040
url: /tr/python-net/conversion/ppsx-to-jpg/ 
keywords: "Convert, PowerPoint, PPSX, JPG, Presentation, Python"
description: PPSX'ten JPG Python'a dönüştürme için örnek kod. PPSX dosyalarını JPG dosyalarına toplu dönüştürme için PowerPoint Python API'sini kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Python'da PPSX'i JPG'ye Dönüştür" h2="PPSX'i JPG'ye dönüştürmek için güçlü PowerPoint Python kitaplığı" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Python'da PPSX'i JPG'ye Dönüştür" %}}

PPSX dosyalarını programlı olarak JPG'ye dönüştürmeniz mi gerekiyor? [*Aspose.Slides for Python aracılığıyla .NET*](https://products.aspose.com/slides/tr/python-net/) kullanarak herhangi bir geliştirici, yalnızca birkaç satır Python koduyla PPSX'i JPG formatına dönüştürebilir.

Modern bir sunum işleme API'si olan Aspose.Slides for Python, PPSX'ten hızlı bir şekilde JPG oluşturur. PPSX'ten JPG'ye dönüştürme kalitesini doğrudan [tarayıcınızda](https://products.aspose.app/slides/conversion/ppt-to-jpg) test edin. Aspose PowerPoint PPTX kitaplığı, PPSX dosyalarını birçok popüler formata dönüştürmenize olanak tanır.

Aşağıdaki pip komutunu kullanarak kitaplığı [PyPI](https://pypi.org/project/Aspose.Slides/) adresinden yükleyebilirsiniz:

{{% blocks/products/pf/agp/code-block title="Konsol/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Python'da PPSX'i JPG'ye Dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, Python kullanarak bir PPSX dosyasını JPG'ye dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunum sınıfının bir örneği ile PPSX dosyasını yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Çıktı dosyası yolunu & SaveFormat.JPG'yi parametre olarak belirtirken 'save' yöntemini çağırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPSX dosyası belirtilen yola kaydedilecek
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Python dönüştürme örnek kaynak kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Linux tabanlı işletim sistemi (bkz. [daha fazla](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 veya üstü
- Projenizde referans verilen Python için Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, PPSX'ten JPG'ye Python Dönüşümünü gösterir" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Python'da PPSX'i JPG olarak kaydedin" %}}
PPSX'ten JPG'ye dönüştürme işleminin bir gösterimini görmek için ücretsiz uygulamayı kullanın. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="PPSX 'a dönüştürmek için ücretsiz uygulama JPG" 
        sectionDescription="[PPT için JPG dönüştürmek için ücretsiz uygulamamızı deneyin.](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca PPSX'i diğer birçok dosya formatına dönüştürebilirsiniz. Aşağıda desteklenen diğer dönüşümleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap Görüntüsü" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Gelişmiş Meta Dosyası Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument Düz XML Sunumu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafik Değişim Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hiper Metin İşaretleme Dili" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument Sunum Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument Standart Biçimi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Taşınabilir Döküman Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-png/" name="PPSX TO PNG" description="taşınabilir Ağ Grafikleri" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Makro Etkin Sunum Dosyası" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Açık XML sunum Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Etiketli Görüntü Formatı" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML Kağıt Özellikleri" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}