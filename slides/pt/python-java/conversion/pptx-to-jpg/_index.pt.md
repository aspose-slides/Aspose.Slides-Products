---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPTX em JPG em Python
url: /pt/python-java/conversion/pptx-to-jpg/
keywords: Conversão de apresentação Python, conversão de apresentações para Python, Python para apresentações, Aspose.Slides Python, conversão de PPTX para JPG, biblioteca de apresentação Python
description: Converta PPTX em JPG em Python. Use a API da biblioteca Python para converter arquivos PPTX em JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converta facilmente PPTX para JPG com Python: Aspose.Slides to the Rescue!" h2="Dê nova vida às suas apresentações com Python. Nosso guia orienta você na conversão de slides existentes do PowerPoint em apresentações envolventes em Python." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converta PPTX em JPG usando Python" variant="code" %}}

Para converter PPTX para JPG, você precisará criar uma apresentação a partir do arquivo PPTX e salvá-la como JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tutorial Python para converter PPTX em JPG" >}}
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
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PPTX em JPG em Python" %}}

Cansado de lutar com softwares de apresentação complexos? Basta procurar [**Aspose.Slides para Python via Java**](https://products.aspose.com/slides/pt/python-java/)! Esta poderosa biblioteca permite criar, editar e converter apresentações entre vários formatos com facilidade. Precisa mudar de PPTX para JPG? Aspose.Slides torna isso muito fácil, exigindo apenas algumas linhas de código Python.

Como uma API de processamento de documentos de última geração, **Aspose.Slides for Python via Java** apresenta velocidades de conversão extremamente rápidas, garantindo a rápida transformação de suas apresentações PPTX para o formato JPG. Livre-se das limitações das ferramentas tradicionais - Aspose.Slides oferece flexibilidade para converter apresentações de PPTX para não apenas JPG, mas também para uma ampla variedade de outros formatos, permitindo que você adapte perfeitamente suas apresentações para qualquer situação.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tutorial Python. Como converter PPTX para JPG usando Aspose.Slides para Python via Java API." intro="Para converter PPTX para JPG usando Aspose.Slides para Python via Java, você precisa importar o pacote para seu script Python e criar uma instância da classe Presentation. A classe Presentation representa um documento PowerPoint e fornece métodos para acessar e manipular seus elementos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para Python via Java**](https://products.aspose.com/slides/pt/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra os arquivos de origem PPTX em Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o resultado como arquivo JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converter PPTX para outros formatos suportados" subTitle="Você também pode converter PPTX e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
