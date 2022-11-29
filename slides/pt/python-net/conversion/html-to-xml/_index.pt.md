---
title: Converter HTML para XML em Python
url: /pt/python-net/conversion/html-to-xml/
keywords: HTML para XML, converter HTML para XML, Python API, Python Library, HTML, XML
description: Converta HTML em XML em Python. Use a API da biblioteca Python para converter arquivos HTML em XMLs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter HTML para XML em Python" h2="Biblioteca Python de plataforma cruzada e de alta velocidade que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter HTML para XML em Python" %}}

[**Aspose.Slides para Python via .NET**](https://products.aspose.com/slides/pt/python-net/) é uma poderosa biblioteca Python para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter HTML em XML. Usando **Aspose.Slides para Python via .NET**, qualquer desenvolvedor ou aplicativo pode converter arquivos HTML em XML com apenas algumas linhas de código Python.

Como uma API moderna de processamento de documentos, o Aspose.Slides for Python exporta arquivos HTML para formatos de arquivo XML rapidamente. A biblioteca Aspose PowerPoint permite converter HTML para XMLs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter HTML para XML usando Python" %}}
Para converter o HTML para XML, você precisará criar a apresentação do arquivo HTML e salvá-lo como XML.

{{% blocks/products/pf/agp/code-block title="Código Python para converter HTML em XML" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open(dataDir + "file.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.xml".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como converter HTML para XML usando Aspose.Slides para Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter HTML em XML em Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale o [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pt/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem HTML em Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo XML.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter HTML para outros formatos suportados" subTitle="Você também pode converter HTML e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}