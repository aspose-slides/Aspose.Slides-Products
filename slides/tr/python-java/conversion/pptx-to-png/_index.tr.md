---
title: Python'da PPTX'ı PNG'a dönüştürün
url: /tr/python-java/conversion/pptx-to-png/
keywords: Python sunum dönüşümü, sunumları Python'a dönüştürme, Sunumlar için Python, Aspose.Slides Python, PPTX'tan PNG'a dönüştürme, Python sunum kitaplığı
description: Python'da PPTX'ı PNG'a dönüştürün. PPTX dosyalarını PNG biçimine dönüştürmek için Python kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python ile PPTX formatını zahmetsizce PNG formatına dönüştürün: Aspose.Slides to the Rescue!" h2="Python ile sunumlarınıza yeni bir soluk getirin. Kılavuzumuz, mevcut PowerPoint slaytlarını ilgi çekici Python sunumlarına dönüştürme konusunda size yol gösterir." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da PPTX'ı PNG'a dönüştürün" %}}

Karmaşık sunum yazılımlarıyla uğraşmaktan bıktınız mı? [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/tr/python-java/)'dan başka bir yere bakmayın! Bu güçlü kitaplık, sunumları kolaylıkla oluşturmanıza, düzenlemenize ve çeşitli formatlar arasında dönüştürmenize olanak tanır. PPTX biçiminden PNG biçimine geçmeniz mi gerekiyor? Aspose.Slides, yalnızca birkaç satır Python kodu gerektirerek bunu çok kolaylaştırır.

Son teknoloji ürünü bir belge işleme API'si olan **Aspose.Slides for Python via Java**, ışık hızında dönüştürme hızlarına sahiptir ve PPTX sunumlarınızın PNG formatına hızla dönüştürülmesini sağlar. Geleneksel araçların sınırlamalarını ortadan kaldırın - Aspose.Slides, sunumlarınızı PPTX formatından yalnızca PNG formatına değil aynı zamanda çok çeşitli diğer formatlara dönüştürme esnekliği sunarak sunumlarınızı her duruma kusursuz bir şekilde uyarlamanıza olanak tanır.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python'u kullanarak PPTX'ı PNG'a dönüştürün" %}}
PPTX dosyasını PNG biçimine dönüştürmek için, PPTX dosyasından Sunum oluşturmanız ve bunu PNG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PPTX'ı PNG'a dönüştürmek için Python eğitimi" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.pptx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Eğitimi. Java API aracılığıyla Aspose.Slides for Python kullanarak PPTX'ı PNG'a dönüştürme." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java aracılığıyla Aspose.Slides for Python'u kullanarak PPTX'ı PNG'a dönüştürmek için paketi Python betiğinize aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/tr/python-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python projenize bir kütüphane referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PPTX dosyalarını Python'da açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PNG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPTX'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca PPTX dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}