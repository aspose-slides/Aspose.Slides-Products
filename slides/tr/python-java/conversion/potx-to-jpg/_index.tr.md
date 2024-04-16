---
title: Python'da POTX'ı JPG'a dönüştürün
url: /tr/python-java/conversion/potx-to-jpg/
keywords: Python sunum dönüşümü, sunumları Python'a dönüştürme, Sunumlar için Python, Aspose.Slides Python, POTX'tan JPG'a dönüştürme, Python sunum kitaplığı
description: Python'da POTX'ı JPG'a dönüştürün. POTX dosyalarını JPG biçimine dönüştürmek için Python kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python ile POTX formatını zahmetsizce JPG formatına dönüştürün: Aspose.Slides to the Rescue!" h2="Python ile sunumlarınıza yeni bir soluk getirin. Kılavuzumuz, mevcut PowerPoint slaytlarını ilgi çekici Python sunumlarına dönüştürme konusunda size yol gösterir." >}}

{{% blocks/products/pf/feature-page-section h2="Python'da POTX'ı JPG'a dönüştürün" %}}

Karmaşık sunum yazılımlarıyla uğraşmaktan bıktınız mı? [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/tr/python-java/)'dan başka bir yere bakmayın! Bu güçlü kitaplık, sunumları kolaylıkla oluşturmanıza, düzenlemenize ve çeşitli formatlar arasında dönüştürmenize olanak tanır. POTX biçiminden JPG biçimine geçmeniz mi gerekiyor? Aspose.Slides, yalnızca birkaç satır Python kodu gerektirerek bunu çok kolaylaştırır.

Son teknoloji ürünü bir belge işleme API'si olan **Aspose.Slides for Python via Java**, ışık hızında dönüştürme hızlarına sahiptir ve POTX sunumlarınızın JPG formatına hızla dönüştürülmesini sağlar. Geleneksel araçların sınırlamalarını ortadan kaldırın - Aspose.Slides, sunumlarınızı POTX formatından yalnızca JPG formatına değil aynı zamanda çok çeşitli diğer formatlara dönüştürme esnekliği sunarak sunumlarınızı her duruma kusursuz bir şekilde uyarlamanıza olanak tanır.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python'u kullanarak POTX'ı JPG'a dönüştürün" %}}
POTX dosyasını JPG biçimine dönüştürmek için, POTX dosyasından Sunum oluşturmanız ve bunu JPG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="POTX'ı JPG'a dönüştürmek için Python eğitimi" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.potx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Eğitimi. Java API aracılığıyla Aspose.Slides for Python kullanarak POTX'ı JPG'a dönüştürme." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java aracılığıyla Aspose.Slides for Python'u kullanarak POTX'ı JPG'a dönüştürmek için paketi Python betiğinize aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/tr/python-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python projenize bir kütüphane referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak POTX dosyalarını Python'da açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu JPG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="POTX'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca POTX dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}