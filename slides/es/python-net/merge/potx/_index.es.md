---
title: Fusionar archivos POTX usando Python
url: /es/python-net/merge/potx/
keywords: Fusionar {desde_formato}, Unirse {desde_formato}, Combinar {desde_formato}, PowerPoint, Presentación, Python, Aspose
description: Combina varios archivos POTX en Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Combinar archivos POTX juntos en Python" h2="API de Python multiplataforma y de alta velocidad que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Combinar POTX en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/) es una poderosa biblioteca de Python para crear y manipular archivos de presentación. Además, proporciona formas flexibles de combinar múltiples presentaciones POTX. Cuando combina una presentación con otra, está combinando efectivamente sus diapositivas en una sola presentación para obtener un archivo. Aspose.Slides le permite fusionar dos presentaciones de diferentes maneras. Puede fusionar presentaciones con todas sus formas, estilos, textos, formato, comentarios, animaciones, etc. sin tener que preocuparse por la pérdida de calidad o datos.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Combinar archivos POTX usando Python" %}}
Para fusionar las presentaciones de PowerPoint, deberá clonar las diapositivas de una presentación a la otra.

{{% blocks/products/pf/agp/code-block title="Código de Python para fusionar múltiples POTX en un solo archivo" offSpacer="true" %}}


```python

import aspose.slides as slides


with slides.Presentation("presentation1.potx") as pres1:
    with slides.Presentation("presentation2.potx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.potx", slides.export.SaveFormat.POTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo fusionar POTX usando Aspose.Slides para la API de Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para fusionar dos archivos POTX y guardar el resultado como POTX en Python." >}}

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
Abra los archivos fuente POTX en Python.
```
pres1 = slides.Presentation('pres1.potx')
pres2 = slides.Presentation('pres2.potx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine archivos POTX usando el método [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde la presentación y obtenga el resultado como un único archivo POTX.
```
pres1.save("result.potx", slides.export.SaveFormat.POTX)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Combinar archivos PDF en línea" sectionDescription="[Cómo fusionar PDF en Python](https://products.aspose.com/slides/es/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportar POTX a otros formatos admitidos" subTitle="También puede combinar POTX y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-pptx/" name="POTX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-ppt/" name="POTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-pdf/" name="POTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-html/" name="POTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-png/" name="POTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-bmp/" name="POTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-jpg/" name="POTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-fodp/" name="POTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-gif/" name="POTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-odp/" name="POTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-otp/" name="POTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-pot/" name="POTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-potm/" name="POTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-pps/" name="POTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-ppsm/" name="POTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-ppsx/" name="POTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-pptm/" name="POTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-svg/" name="POTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-tiff/" name="POTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/merge/potx-to-xps/" name="POTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}