---
title: Mesclar arquivos PPTM usando Python
url: /pt/python-net/merge/pptm/
keywords: Mesclar PPTM, Unir PPTM, Combinar PPTM, PowerPoint, Apresentação, Python, Aspose
description: Mescle vários arquivos PPTM em Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Mesclar arquivos PPTM juntos em Python" h2="API Python de alta velocidade e plataforma cruzada que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de nenhum software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Mesclar PPTM em Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pt/python-net/) é uma poderosa biblioteca Python para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de combinar várias apresentações PPTM. Ao mesclar uma apresentação com outra, você está efetivamente combinando seus slides em uma única apresentação para obter um arquivo. Aspose.Slides permite mesclar duas apresentações de maneiras diferentes. Você pode mesclar apresentações com todas as suas formas, estilos, textos, formatação, comentários, animações, etc. sem ter que se preocupar com perda de qualidade ou dados.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mesclar arquivos PPTM usando Python" %}}
Para mesclar as apresentações do PowerPoint, você precisará clonar os slides de uma apresentação para outra.

{{% blocks/products/pf/agp/code-block title="Código Python para mesclar vários PPTM em um único arquivo" offSpacer="true" %}}


```python

import aspose.slides as slides


with slides.Presentation("presentation1.pptm") as pres1:
    with slides.Presentation("presentation2.pptm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pptm", slides.export.SaveFormat.PPTM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como mesclar PPTM usando Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para mesclar dois arquivos PPTM e salvar o resultado como PPTM em Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale o [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pt/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Python.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem PPTM em Python.
```
pres1 = slides.Presentation('pres1.pptm')
pres2 = slides.Presentation('pres2.pptm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine arquivos PPTM usando o método [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve a apresentação e obtenha o resultado como um único arquivo PPTM.
```
pres1.save("result.pptm", slides.export.SaveFormat.PPTM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportar PPTM para outros formatos suportados" subTitle="Você também pode combinar PPTM e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-pptx/" name="PPTM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-ppt/" name="PPTM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-pdf/" name="PPTM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-html/" name="PPTM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-png/" name="PPTM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-bmp/" name="PPTM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-jpg/" name="PPTM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-fodp/" name="PPTM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-gif/" name="PPTM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-odp/" name="PPTM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-otp/" name="PPTM TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-pot/" name="PPTM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-potm/" name="PPTM TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-potx/" name="PPTM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-pps/" name="PPTM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-ppsm/" name="PPTM TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-ppsx/" name="PPTM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-svg/" name="PPTM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-tiff/" name="PPTM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/pptm-to-xps/" name="PPTM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}