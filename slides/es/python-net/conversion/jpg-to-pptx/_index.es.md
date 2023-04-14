---
title: Convertir JPG a PPTX en Python
url: /es/python-net/conversion/jpg-to-pptx/
keywords: Convierta JPG a PPTX, JPG a PPTX, PowerPoint, JPG, PPTX, API de Python, biblioteca de Python
description: Convierta JPG a PPTX en Python. Use la API de la biblioteca de Python para convertir imágenes JPG a PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir JPG a PPTX en Python" h2="Potente API Python multiplataforma para convertir JPG a PPTX usando código Python" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta JPG a PPTX usando Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/) es una poderosa biblioteca de Python que se utiliza para crear, convertir y manipular presentaciones de PowerPoint, archivos PDF, documentos HTML y otros archivos. Cuando convierte JPG a PPTX, básicamente está creando una presentación de PowerPoint que contiene diapositivas basadas en imágenes JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convertir JPG a PPTX en Python" %}}
Con [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/), puede convertir una imagen JPG en una presentación de PowerPoint con solo unas pocas líneas de código:

{{% blocks/products/pf/agp/code-block title="Código de Python para convertir JPG a PPTX" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cómo convertir JPG a PPTX en Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para Python a través de .NET**. Consulte [**Instalación**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue la biblioteca como referencia en su proyecto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea una instancia de la clase Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue la imagen JPG que desea convertir a PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el archivo resultante como una presentación PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones de PowerPoint admitidas" subTitle="También puede convertir archivos en otros formatos a PowerPoint" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}