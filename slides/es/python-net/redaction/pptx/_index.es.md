---
title: Redactar PPTX archivos de presentación usando Python
url: /es/python-net/redaction/pptx/
keywords: Redactar PPTX, buscar y reemplazar texto en PPTX, actualizar PPTX Presentación
description: Código fuente de Python para buscar y reemplazar texto en la presentación PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redactar PPTX usando Python" h2="Cree sus propias aplicaciones Python para buscar y reemplazar texto en archivos de presentación utilizando las API del lado del servidor. Aprenda a buscar y reemplazar texto en contenido, comentarios o metadatos de presentaciones PPTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redactar PPTX presentación a través de Python" %}}
Se puede realizar una búsqueda básica de documentos y reemplazar texto en contenidos, comentarios, notas de diapositivas o metadatos con las API de Aspose.Slides for Python via .NET con solo unas pocas líneas de código. Busque y reemplace texto en PowerPoint y OpenOffice. Edite texto, comentarios, metadatos en la presentación a través de la coincidencia de datos de expresiones regulares.
{{% blocks/products/pf/agp/code-block title="Redactar la presentación PPTX usando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo redactar PPTX a través de Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para Redactar archivos PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue PPTX con una instancia de Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use el método [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) para buscar y reemplazar texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de redacción PPTX en línea" sectionDescription="Busque y reemplace texto en contenidos, comentarios o metadatos en documentos PPTX ahora mismo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de redacción admitidos" subTitle="Usando Python, también puede redactar los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}