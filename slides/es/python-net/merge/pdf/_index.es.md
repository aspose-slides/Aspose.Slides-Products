---
title: Fusionar archivos PDF usando Python
url: /es/python-net/merge/pdf/
keywords: Fusionar {desde_formato}, Unirse {desde_formato}, Combinar {desde_formato}, PowerPoint, Presentación, Python, Aspose
description: Combina varios archivos PDF en Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Combinar archivos PDF juntos en Python" h2="API de Python multiplataforma y de alta velocidad que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Combinar PDF en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/) es una poderosa biblioteca de Python para crear y manipular archivos de presentación. Además, proporciona formas flexibles de combinar múltiples presentaciones PDF. Cuando combina una presentación con otra, está combinando efectivamente sus diapositivas en una sola presentación para obtener un archivo. Aspose.Slides le permite fusionar dos presentaciones de diferentes maneras. Puede fusionar presentaciones con todas sus formas, estilos, textos, formato, comentarios, animaciones, etc. sin tener que preocuparse por la pérdida de calidad o datos.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Combinar archivos PDF usando Python" %}}
Para fusionar las presentaciones de PowerPoint, deberá clonar las diapositivas de una presentación a la otra.

{{% blocks/products/pf/agp/code-block title="Código de Python para fusionar múltiples PDF en un solo archivo" offSpacer="true" %}}


```python

import aspose.slides as slides


with slides.Presentation() as pres1:
    pres1.slides.remove_at(0)
    pres1.slides.add_from_pdf("document1.pdf")
    with slides.Presentation() as pres2:
        pres2.slides.remove_at(0)
        pres2.slides.add_from_pdf("document2.pdf")
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo fusionar PDF usando Aspose.Slides para la API de Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para fusionar dos archivos PDF y guardar el resultado como PDF en Python." >}}

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
Abra los archivos fuente PDF en Python.
```
pres1 = slides.Presentation('pres1.pdf')
pres2 = slides.Presentation('pres2.pdf')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine archivos PDF usando el método [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde la presentación y obtenga el resultado como un único archivo PDF.
```
pres1.save("result.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportar PDF a otros formatos admitidos" subTitle="También puede combinar PDF y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-pptx/" name="PDF TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-ppt/" name="PDF TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-html/" name="PDF TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-png/" name="PDF TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-bmp/" name="PDF TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-jpg/" name="PDF TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-fodp/" name="PDF TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-gif/" name="PDF TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-odp/" name="PDF TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-otp/" name="PDF TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-pot/" name="PDF TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-potm/" name="PDF TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-potx/" name="PDF TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-pps/" name="PDF TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-ppsm/" name="PDF TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-ppsx/" name="PDF TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-pptm/" name="PDF TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-svg/" name="PDF TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-tiff/" name="PDF TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/pdf-to-xps/" name="PDF TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}