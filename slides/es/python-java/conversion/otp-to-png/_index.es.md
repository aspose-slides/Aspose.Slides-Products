---
title: Convertir OTP a PNG en Python
url: /es/python-java/conversion/otp-to-png/
keywords: Conversión de presentaciones de Python, convertir presentaciones a Python, Python para presentaciones, Aspose.Slides Python, conversión de OTP a PNG, biblioteca de presentaciones de Python
description: Convierta OTP a PNG en Python. Utilice la API de la biblioteca Python para convertir archivos OTP a PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convierta OTP a PNG sin esfuerzo con Python: ¡Aspose.Slides to the Rescue!" h2="Dale nueva vida a tus presentaciones con Python. Nuestra guía le guiará en la conversión de diapositivas de PowerPoint existentes en atractivas presentaciones de Python." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir OTP a PNG en Python" %}}

¿Estás cansado de luchar con software de presentación complejo? ¡No busques más que [**Aspose.Slides para Python vía Java**](https://products.aspose.com/slides/es/python-java/)! Esta poderosa biblioteca le permite crear, editar y convertir presentaciones entre varios formatos con facilidad. ¿Necesitas cambiar de OTP a PNG? Aspose.Slides lo hace muy sencillo y solo requiere unas pocas líneas de código Python.

Como API de procesamiento de documentos de vanguardia, **Aspose.Slides para Python a través de Java** cuenta con velocidades de conversión ultrarrápidas, lo que garantiza una rápida transformación de sus presentaciones OTP al formato PNG. Olvídese de las limitaciones de las herramientas tradicionales: Aspose.Slides le brinda la flexibilidad de convertir presentaciones de OTP no solo a PNG sino también a una amplia gama de otros formatos, lo que le permite adaptar perfectamente sus presentaciones a cualquier situación.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta OTP a PNG usando Python" %}}
Para convertir OTP a PNG, deberá crear una presentación a partir del archivo OTP y guardarla como PNG.

{{% blocks/products/pf/agp/code-block title="Tutorial de Python para convertir OTP en PNG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.otp");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Tutorial de Python. Cómo convertir OTP a PNG usando Aspose.Slides para Python a través de la API de Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Para convertir OTP a PNG usando Aspose.Slides para Python a través de Java, debe importar el paquete a su secuencia de comandos Python y crear una instancia de la clase Presentación. La clase Presentación representa un documento de PowerPoint y proporciona métodos para acceder y manipular sus elementos." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Python a través de Java**](https://products.aspose.com/slides/es/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente OTP en Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el resultado como archivo PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir OTP a otros formatos admitidos" subTitle="También puede convertir OTP y guardarlo en otros formatos de archivo. Vea todos los formatos compatibles a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-java/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}