---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPSX a JPG en Python
url: /es/python-java/conversion/ppsx-to-jpg/
keywords: Conversión de presentaciones de Python, convertir presentaciones a Python, Python para presentaciones, Aspose.Slides Python, conversión de PPSX a JPG, biblioteca de presentaciones de Python
description: Convierta PPSX a JPG en Python. Utilice la API de la biblioteca Python para convertir archivos PPSX a JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convierta PPSX a JPG sin esfuerzo con Python: ¡Aspose.Slides to the Rescue!" h2="Dale nueva vida a tus presentaciones con Python. Nuestra guía le guiará en la conversión de diapositivas de PowerPoint existentes en atractivas presentaciones de Python." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta PPSX a JPG usando Python" variant="code" %}}

Para convertir PPSX a JPG, deberá crear una presentación a partir del archivo PPSX y guardarla como JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tutorial de Python para convertir PPSX en JPG" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppsx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PPSX a JPG en Python" %}}

¿Estás cansado de luchar con software de presentación complejo? ¡No busques más que [**Aspose.Slides para Python vía Java**](https://products.aspose.com/slides/es/python-java/)! Esta poderosa biblioteca le permite crear, editar y convertir presentaciones entre varios formatos con facilidad. ¿Necesitas cambiar de PPSX a JPG? Aspose.Slides lo hace muy sencillo y solo requiere unas pocas líneas de código Python.

Como API de procesamiento de documentos de vanguardia, **Aspose.Slides para Python a través de Java** cuenta con velocidades de conversión ultrarrápidas, lo que garantiza una rápida transformación de sus presentaciones PPSX al formato JPG. Olvídese de las limitaciones de las herramientas tradicionales: Aspose.Slides le brinda la flexibilidad de convertir presentaciones de PPSX no solo a JPG sino también a una amplia gama de otros formatos, lo que le permite adaptar perfectamente sus presentaciones a cualquier situación.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tutorial de Python. Cómo convertir PPSX a JPG usando Aspose.Slides para Python a través de la API de Java." intro="Para convertir PPSX a JPG usando Aspose.Slides para Python a través de Java, debe importar el paquete a su secuencia de comandos Python y crear una instancia de la clase Presentación. La clase Presentación representa un documento de PowerPoint y proporciona métodos para acceder y manipular sus elementos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para Python a través de Java**](https://products.aspose.com/slides/es/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra los archivos fuente PPSX en Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el resultado como archivo JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PPSX a otros formatos admitidos" subTitle="También puede convertir PPSX y guardarlo en otros formatos de archivo. Vea todos los formatos compatibles a continuación" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
