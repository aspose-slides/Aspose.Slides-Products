---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir HTML a PPTX en Python
url: /es/python-net/conversion/html-to-pptx/
keywords: Convierta HTML a PPTX, HTML a PPTX, PowerPoint, HTML, PPTX, API de Python, biblioteca de Python
description: Convierta HTML a PPTX en Python. Use la API de la biblioteca de Python para convertir HTML a PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir HTML a PPTX en Python" h2="Potente API Python multiplataforma para convertir HTML a PPTX usando código Python" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir HTML a PPTX en Python" variant="code" %}}

Con [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/), puede convertir un documento HTML en una presentación de PowerPoint con solo unas pocas líneas de código:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código Python para convertir HTML a PPTX" >}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rb") as htmlStream:
        pres.slides.add_from_html(htmlStream)

    pres.save("MyPresentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta HTML a PPTX usando Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/es/python-net/) es una poderosa biblioteca de Python que se utiliza para crear, convertir y manipular presentaciones de PowerPoint, archivos PDF, documentos HTML y otros archivos. Cuando convierte HTML a PPTX, básicamente está moviendo el contenido de un documento HTML a diapositivas en una presentación de PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir HTML a PPTX en Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale **Aspose.Slides para Python a través de .NET**. Consulte [**Instalación**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue la biblioteca como referencia en su proyecto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea una instancia de la clase Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el documento HTML que desea convertir a PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo resultante como una presentación PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertidor en línea gratuito"
  description="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones de PowerPoint admitidas" subTitle="También puede convertir archivos en otros formatos a PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
