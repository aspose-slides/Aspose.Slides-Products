---
title: Python'da FODP'ı SVG'a dönüştürün
url: /tr/python-java/conversion/fodp-to-svg/
keywords: Python sunum dönüşümü, sunumları Python'a dönüştürme, Sunumlar için Python, Aspose.Slides Python, FODP'tan SVG'a dönüştürme, Python sunum kitaplığı
description: Python'da FODP'ı SVG'a dönüştürün. FODP dosyalarını SVG biçimine dönüştürmek için Python kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python ile FODP formatını zahmetsizce SVG formatına dönüştürün: Aspose.Slides to the Rescue!" h2="Python ile sunumlarınıza yeni bir soluk getirin. Kılavuzumuz, mevcut PowerPoint slaytlarını ilgi çekici Python sunumlarına dönüştürme konusunda size yol gösterir." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da FODP'ı SVG'a dönüştürün" %}}

Karmaşık sunum yazılımlarıyla uğraşmaktan bıktınız mı? [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/tr/python-java/)'dan başka bir yere bakmayın! Bu güçlü kitaplık, sunumları kolaylıkla oluşturmanıza, düzenlemenize ve çeşitli formatlar arasında dönüştürmenize olanak tanır. FODP biçiminden SVG biçimine geçmeniz mi gerekiyor? Aspose.Slides, yalnızca birkaç satır Python kodu gerektirerek bunu çok kolaylaştırır.

Son teknoloji ürünü bir belge işleme API'si olan **Aspose.Slides for Python via Java**, ışık hızında dönüştürme hızlarına sahiptir ve FODP sunumlarınızın SVG formatına hızla dönüştürülmesini sağlar. Geleneksel araçların sınırlamalarını ortadan kaldırın - Aspose.Slides, sunumlarınızı FODP formatından yalnızca SVG formatına değil aynı zamanda çok çeşitli diğer formatlara dönüştürme esnekliği sunarak sunumlarınızı her duruma kusursuz bir şekilde uyarlamanıza olanak tanır.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python'u kullanarak FODP'ı SVG'a dönüştürün" %}}
FODP dosyasını SVG biçimine dönüştürmek için, FODP dosyasından Sunum oluşturmanız ve bunu SVG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="FODP'ı SVG'a dönüştürmek için Python eğitimi" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.fodp");

for i in range(pres.getSlides().size()):
    outputStream = open('slide" + i + ".svg', "wb")
    outputStream.write(Slide.writeAsSvgToBytes(pres.getSlides().get_Item(i)))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Eğitimi. Java API aracılığıyla Aspose.Slides for Python kullanarak FODP'ı SVG'a dönüştürme." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java aracılığıyla Aspose.Slides for Python'u kullanarak FODP'ı SVG'a dönüştürmek için paketi Python betiğinize aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/tr/python-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python projenize bir kütüphane referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak FODP dosyalarını Python'da açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu SVG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="FODP'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca FODP dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}