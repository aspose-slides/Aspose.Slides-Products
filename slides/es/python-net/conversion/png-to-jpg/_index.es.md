---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PNG a JPG en Python
url: /es/python-net/conversion/png-to-jpg/
keywords: PNG a JPG, convertir PNG a JPG, API de Python, biblioteca de Python, PNG, JPG
description: Convierte PNG a JPG en Python. Use la API de la biblioteca de Python para convertir archivos PNG a JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PNG a JPG en Python" h2="Biblioteca Python de alta velocidad y multiplataforma que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta PNG a JPG usando Python" variant="code" %}}

Para convertir PNG a JPG, deberá crear la presentación desde el archivo PNG y guardarlo como JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código de Python para convertir PNG en JPG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PNG a JPG en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/) es una poderosa biblioteca de Python para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PNG a JPG. Con **Aspose.Slides para Python a través de .NET**, cualquier desarrollador o aplicación puede convertir archivos PNG a JPG con solo unas pocas líneas de código Python.

Como una API moderna de procesamiento de documentos, Aspose.Slides para Python exporta archivos PNG a formatos de archivo JPG rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir PNG a JPGs y muchos otros formatos de archivo

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir PNG a JPG usando Aspose.Slides para la API de Python" intro="Estos son los pasos para convertir PNG a JPG en Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto de Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra los archivos fuente PNG en Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guardar resultado como archivo JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Creado con Aspose.Slides" title="Convertir PNG a JPG en línea" description="La aplicación gratuita Aspose.Slides Conversion está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PNG." button="Abrir Aspose.Slides Conversion" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" upload="Arrastre o suba su archivo" saveAs="Guardar como" convert="Convertir" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides convierte archivos antes de escribir código.
- Suba archivos PNG y guárdelos como JPG.
- Descargue el resultado o convierta más archivos.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PNG a otros formatos admitidos" subTitle="También puede convertir PNG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
