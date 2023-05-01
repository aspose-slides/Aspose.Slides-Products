---
title: Extraiga texto e imágenes de archivos PPT usando Python
url: /es/python-net/parser/ppt/
keywords: analizar PPT con Python, PPT analizar Python, extraer datos de PPT en Python, extraer texto de PPT con Python, extraer imágenes de PPT con Python
description: Código fuente de Python para analizar la presentación de PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extraiga texto e imágenes de la presentación PPT usando Python" h2="Cree sus propias aplicaciones de Python para extraer archivos de texto, imagen, video y audio de PowerPoint utilizando las API del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Extraer texto de la presentación PPT a través de Python" %}}
Para escanear el texto de toda la presentación, use el método estático [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) expuesto por la clase SlideUtil. El siguiente código escanea el texto y la información de formato de una presentación, incluidas las diapositivas maestras.
{{% blocks/products/pf/agp/code-block title="Extraer texto de la presentación PPT usando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPT file
with slides.Presentation("pres.ppt") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPT
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo extraer texto de PPT a través de Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para analizar archivos PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue PPT con una instancia de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenga una matriz de objetos TextFrame de todas las diapositivas en PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bucle a través de la matriz de TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Recorrer los párrafos en el TextFrame actual
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bucle a través de porciones en el párrafo actual
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtener texto en la parte actual
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de análisis admitidos" subTitle="Usando Python, también puede escanear los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}