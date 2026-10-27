---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python'da PPT'yi JPG'ye Dönüştür
weight: 2260
url: /tr/python-net/conversion/ppt-to-jpg/ 
keywords: "Convert, PowerPoint, PPT, JPG, Presentation, Python"
description: PPT'den JPG'ye Python dönüşümü için örnek kod. PPT dosyalarını JPG dosyalarına toplu dönüştürmek için PowerPoint Python API'sini kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python'da PPT'yi JPG'ye Dönüştür" h2="PPT'yi JPG'ye dönüştürmek için güçlü PowerPoint Python kitaplığı"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python'da PPT'yi JPG'ye Dönüştür" %}}

PPT dosyalarını programlı olarak JPG'ye dönüştürmeniz mi gerekiyor? [*Aspose.Slides for Python aracılığıyla .NET*](https://products.aspose.com/slides/tr/python-net/) kullanarak herhangi bir geliştirici, yalnızca birkaç satır Python koduyla PPT'yi JPG formatına dönüştürebilir.

Modern bir sunum işleme API'si olan Aspose.Slides for Python, PPT'den hızlı bir şekilde JPG oluşturur. PPT'den JPG'ye dönüştürme kalitesini doğrudan [tarayıcınızda](https://products.aspose.app/slides/conversion) test edin. Aspose PowerPoint PPTX kitaplığı, PPT dosyalarını birçok popüler formata dönüştürmenize olanak tanır.

Aşağıdaki pip komutunu kullanarak kitaplığı [PyPI](https://pypi.org/project/Aspose.Slides/) adresinden yükleyebilirsiniz:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python'da PPT'yi JPG olarak kaydedin" %}}

PPT'den JPG'ye dönüştürme işleminin bir gösterimini görmek için ücretsiz uygulamayı kullanın.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bu örnek kod, PPT'den JPG'ye Python Dönüşümünü gösterir" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python'da PPT'yi JPG'ye Dönüştürme" intro="Bunlar, Python kullanarak bir PPT dosyasını JPG'ye dönüştürme adımlarıdır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunum sınıfının bir örneği ile PPT dosyasını yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu & SaveFormat.JPG'yi parametre olarak belirtirken 'save' yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyası belirtilen yola kaydedilecek{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="Python dönüştürme örnek kaynak kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun." %}}

- Microsoft Windows veya Linux tabanlı işletim sistemi (bkz. [daha fazla](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 veya üstü
- Projenizde referans verilen Python için Aspose.Slides.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides ile geliştirildi" title="PPT dosyasını çevrimiçi olarak JPG biçimine dönüştürün" description="Ücretsiz Aspose.Slides Conversion uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Conversion uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" upload="Dosyanızı bırakın veya yükleyin" saveAs="Farklı kaydet" convert="Dönüştür" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyaları nasıl dönüştürdüğünü görün.
- PPT dosyalarını yükleyin ve JPG olarak kaydedin.
- Sonucu indirin veya daha fazla dosya dönüştürün.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="PPT'yi diğer birçok dosya formatına da dönüştürebilirsiniz. Aşağıda desteklenen diğer dönüşümleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap Görüntüsü" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Gelişmiş Meta Dosyası Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-fodp/" name="PPT TO FODP" description="OpenDocument Düz XML Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Grafik Değişim Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hiper Metin İşaretleme Dili" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument Sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument Standart Biçimi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Taşınabilir Döküman Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-png/" name="PPT TO PNG" description="taşınabilir Ağ Grafikleri" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint Slayt Gösterisi" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Makro Etkin Sunum Dosyası" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Açık XML sunum Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-svg/" name="PPT TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Etiketli Görüntü Formatı" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
