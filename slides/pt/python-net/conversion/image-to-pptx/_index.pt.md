---
title: Converter imagem para PPTX em Python
url: /pt/python-net/conversion/image-to-pptx/
keywords: Imagem para PPTX, Converter imagem para PPTX, API Python, Biblioteca Python, Imagem, PPTX
description: Converter imagem para PPTX em Python. Use a API da biblioteca Python para converter arquivos de imagem em PDFs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter imagem para PPTX em Python" h2="Biblioteca Python de plataforma cruzada e de alta velocidade que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter imagem para PPTX em Python" %}}

[**Aspose.Slides para Python via .NET**](https://products.aspose.com/slides/pt/python-net/) é uma poderosa biblioteca Python para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter imagens em PPTX. Usando **Aspose.Slides para Python via .NET**, qualquer desenvolvedor ou aplicativo pode converter imagens em arquivos PPTX com apenas algumas linhas de código Python.

Como uma API moderna de processamento de documentos, o Aspose.Slides for Python exporta arquivos de imagem para formatos de arquivo PPTX rapidamente. A biblioteca Aspose PowerPoint permite converter imagens em PDFs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter imagem em PPTX usando Python" %}}
Para converter a imagem em PPTX, você precisará criar uma apresentação a partir do arquivo de imagem e salvá-la como PPTX.

{{% blocks/products/pf/agp/code-block title="Código Python para converter imagem em PPTX" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.pptx", slides.export.SaveFormat.PPTX)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como converter imagem para PPTX usando Aspose.Slides para Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter imagem em PPTX em Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale o [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pt/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de imagem de origem em Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Conversor Online Gratuito" sectionDescription="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter imagem para outros formatos suportados" subTitle="Você também pode converter a imagem e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}