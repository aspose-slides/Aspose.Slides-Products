---
title: Converter JPG para PDF em Python
url: /pt/python-net/conversion/jpg-to-pdf/
keywords: JPG para PDF, converter JPG para PDF, Python API, Python Library, JPG, PDF
description: Converta JPG em PDF em Python. Use a API da biblioteca Python para converter arquivos JPG em PDFs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter JPG para PDF em Python" h2="Biblioteca Python de plataforma cruzada e de alta velocidade que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter JPG para PDF em Python" %}}

[**Aspose.Slides para Python via .NET**](https://products.aspose.com/slides/pt/python-net/) é uma poderosa biblioteca Python para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter JPG em PDF. Usando **Aspose.Slides para Python via .NET**, qualquer desenvolvedor ou aplicativo pode converter arquivos JPG em PDF com apenas algumas linhas de código Python.

Como uma API moderna de processamento de documentos, o Aspose.Slides for Python exporta arquivos JPG para formatos de arquivo PDF rapidamente. A biblioteca Aspose PowerPoint permite converter JPG para PDFs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter JPG para PDF usando Python" %}}
Para converter o JPG para PDF, você precisará criar a apresentação do arquivo JPG e salvá-lo como PDF.

{{% blocks/products/pf/agp/code-block title="Código Python para converter JPG em PDF" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como converter JPG para PDF usando Aspose.Slides para Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter JPG em PDF em Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale o [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pt/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem JPG em Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Conversor Online Gratuito" sectionDescription="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter JPG para outros formatos suportados" subTitle="Você também pode converter JPG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}