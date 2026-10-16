---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir FODP a SVG en Python
url: /es/python-java/conversion/fodp-to-svg/
keywords: Conversión de presentaciones de Python, convertir presentaciones a Python, Python para presentaciones, Aspose.Slides Python, conversión de FODP a SVG, biblioteca de presentaciones de Python
description: Convierta FODP a SVG en Python. Utilice la API de la biblioteca Python para convertir archivos FODP a SVG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convierta FODP a SVG sin esfuerzo con Python: ¡Aspose.Slides to the Rescue!" h2="Dale nueva vida a tus presentaciones con Python. Nuestra guía le guiará en la conversión de diapositivas de PowerPoint existentes en atractivas presentaciones de Python." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta FODP a SVG usando Python" variant="code" %}}

Para convertir FODP a SVG, deberá crear una presentación a partir del archivo FODP y guardarla como SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tutorial de Python para convertir FODP en SVG" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.fodp");

for i in range(pres.getSlides().size()):
    outputStream = open('slide" + i + ".svg', "wb")
    outputStream.write(Slide.writeAsSvgToBytes(pres.getSlides().get_Item(i)))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir FODP a SVG en Python" %}}

¿Estás cansado de luchar con software de presentación complejo? ¡No busques más que [**Aspose.Slides para Python vía Java**](https://products.aspose.com/slides/es/python-java/)! Esta poderosa biblioteca le permite crear, editar y convertir presentaciones entre varios formatos con facilidad. ¿Necesitas cambiar de FODP a SVG? Aspose.Slides lo hace muy sencillo y solo requiere unas pocas líneas de código Python.

Como API de procesamiento de documentos de vanguardia, **Aspose.Slides para Python a través de Java** cuenta con velocidades de conversión ultrarrápidas, lo que garantiza una rápida transformación de sus presentaciones FODP al formato SVG. Olvídese de las limitaciones de las herramientas tradicionales: Aspose.Slides le brinda la flexibilidad de convertir presentaciones de FODP no solo a SVG sino también a una amplia gama de otros formatos, lo que le permite adaptar perfectamente sus presentaciones a cualquier situación.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tutorial de Python. Cómo convertir FODP a SVG usando Aspose.Slides para Python a través de la API de Java." intro="Para convertir FODP a SVG usando Aspose.Slides para Python a través de Java, debe importar el paquete a su secuencia de comandos Python y crear una instancia de la clase Presentación. La clase Presentación representa un documento de PowerPoint y proporciona métodos para acceder y manipular sus elementos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para Python a través de Java**](https://products.aspose.com/slides/es/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra los archivos fuente FODP en Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el resultado como archivo SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir FODP a otros formatos admitidos" subTitle="También puede convertir FODP y guardarlo en otros formatos de archivo. Vea todos los formatos compatibles a continuación" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
