---
title: Convertir PNG a PDF en Python
url: /es/python-net/conversion/png-to-pdf/
keywords: PNG a PDF, convertir PNG a PDF, API de Python, biblioteca de Python, PNG, PDF
description: Convierte PNG a PDF en Python. Use la API de la biblioteca de Python para convertir archivos PNG a PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PNG a PDF en Python" h2="Biblioteca Python de alta velocidad y multiplataforma que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PNG a PDF en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/) es una poderosa biblioteca de Python para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PNG a PDF. Con **Aspose.Slides para Python a través de .NET**, cualquier desarrollador o aplicación puede convertir archivos PNG a PDF con solo unas pocas líneas de código Python.

Como una API moderna de procesamiento de documentos, Aspose.Slides para Python exporta archivos PNG a formatos de archivo PDF rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir PNG a PDFs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta PNG a PDF usando Python" %}}
Para convertir PNG a PDF, deberá crear la presentación desde el archivo PNG y guardarlo como PDF.

{{% blocks/products/pf/agp/code-block title="Código de Python para convertir PNG en PDF" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PNG a PDF usando Aspose.Slides para la API de Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir PNG a PDF en Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto de Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente PNG en Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PNG a otros formatos admitidos" subTitle="También puede convertir PNG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}