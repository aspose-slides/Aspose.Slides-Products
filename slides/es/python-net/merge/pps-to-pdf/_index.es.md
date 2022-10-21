---
title: Fusionar archivos PPS a PDF usando Python
url: /es/python-net/merge/pps-to-pdf/
keywords: Combinar PPS a PDF, unir PPS a PDF, combinar PPS a PDF, PowerPoint, Presentation, PDF, Python, Aspose
description: Combina varios archivos PPS en Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Combinar archivos PPS a PDF juntos en Python" h2="API de Python multiplataforma y de alta velocidad que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Combinar PPS a PDF en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/) es una poderosa biblioteca de Python para crear y manipular archivos de presentación. Además, proporciona formas flexibles de combinar múltiples presentaciones PPS. Cuando combina una presentación con otra, está combinando efectivamente sus diapositivas en una sola presentación para obtener un archivo. Aspose.Slides le permite fusionar dos presentaciones de diferentes maneras. Puede fusionar presentaciones con todas sus formas, estilos, textos, formato, comentarios, animaciones, etc. sin tener que preocuparse por la pérdida de calidad o datos.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Combinar archivos PPS a PDF usando Python" %}}
Para fusionar las presentaciones de PowerPoint, deberá clonar las diapositivas de una presentación a la otra.

{{% blocks/products/pf/agp/code-block title="Código de Python para fusionar múltiples PPS en un solo archivo PDF" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pps") as pres1:
    with slides.Presentation("presentation2.pps") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo fusionar PPS a PDF usando Aspose.Slides para la API de Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para fusionar dos archivos PPS y guardar el resultado como PDF en Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto de Python.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente PPS en Python.
```
pres1 = slides.Presentation('pres1.pps')
pres2 = slides.Presentation('pres2.pps')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine archivos PPS usando el método [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde la presentación y obtenga el resultado como un único archivo PDF.
```
pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportar PPS a otros formatos admitidos" subTitle="También puede combinar PPS y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-pptx/" name="PPS TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-ppt/" name="PPS TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-html/" name="PPS TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-png/" name="PPS TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-bmp/" name="PPS TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-jpg/" name="PPS TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-fodp/" name="PPS TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-gif/" name="PPS TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-odp/" name="PPS TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-otp/" name="PPS TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-pot/" name="PPS TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-potm/" name="PPS TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-potx/" name="PPS TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-ppsm/" name="PPS TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-ppsx/" name="PPS TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-pptm/" name="PPS TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-svg/" name="PPS TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-tiff/" name="PPS TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pps-to-xps/" name="PPS TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}