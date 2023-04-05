---
title: Mesclar arquivos PPSX para FODP usando Python
url: /pt/python-net/merge/ppsx-to-fodp/
keywords: Mesclar PPSX com FODP, juntar PPSX com FODP, combinar PPSX com FODP, PowerPoint, Presentation, FODP, Python, Aspose
description: Mescle vários arquivos PPSX em Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Mesclar arquivos PPSX para FODP juntos em Python" h2="API Python de alta velocidade e plataforma cruzada que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de nenhum software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Mesclar PPSX para FODP em Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pt/python-net/) é uma poderosa biblioteca Python para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de combinar várias apresentações PPSX. Ao mesclar uma apresentação com outra, você está efetivamente combinando seus slides em uma única apresentação para obter um arquivo. Aspose.Slides permite mesclar duas apresentações de maneiras diferentes. Você pode mesclar apresentações com todas as suas formas, estilos, textos, formatação, comentários, animações, etc. sem ter que se preocupar com perda de qualidade ou dados.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mesclar arquivos PPSX para FODP usando Python" %}}
Para mesclar as apresentações do PowerPoint, você precisará clonar os slides de uma apresentação para outra.

{{% blocks/products/pf/agp/code-block title="Código Python para mesclar vários PPSX em um único arquivo FODP" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.ppsx") as pres1:
    with slides.Presentation("presentation2.ppsx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.fodp", slides.export.SaveFormat.FODP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como mesclar PPSX para FODP usando Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para mesclar dois arquivos PPSX e salvar o resultado como FODP em Python." >}}

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
Abra os arquivos de origem PPSX em Python.
```
pres1 = slides.Presentation('pres1.ppsx')
pres2 = slides.Presentation('pres2.ppsx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine arquivos PPSX usando o método [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve a apresentação e obtenha o resultado como um único arquivo FODP.
```
pres1.save("presentation.fodp", slides.export.SaveFormat.FODP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Mesclar arquivos PDF on-line" sectionDescription="[Como mesclar PDF em Python](https://products.aspose.com/slides/pt/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportar PPSX para outros formatos suportados" subTitle="Você também pode combinar PPSX e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-pptx/" name="PPSX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-ppt/" name="PPSX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-pdf/" name="PPSX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-html/" name="PPSX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-png/" name="PPSX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-bmp/" name="PPSX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-jpg/" name="PPSX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-gif/" name="PPSX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-odp/" name="PPSX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-otp/" name="PPSX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-pot/" name="PPSX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-potm/" name="PPSX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-potx/" name="PPSX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-pps/" name="PPSX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-pptm/" name="PPSX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-svg/" name="PPSX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-tiff/" name="PPSX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/merge/ppsx-to-xps/" name="PPSX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}