---
title: Extraia texto e imagens de arquivos PPT usando Python
url: /pt/python-net/parser/ppt/
keywords: analisar PPT usando Python, analisar PPT Python, extrair dados de PPT em Python, extrair texto de PPT usando Python, extrair imagens de PPT usando Python
description: Código-fonte Python para analisar a apresentação PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extraia texto e imagens da apresentação PPT usando Python" h2="Crie seus próprios aplicativos Python para extrair arquivos de texto, imagem, vídeo e áudio do PowerPoint usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Extrair texto da apresentação PPT via Python" %}}
Para digitalizar o texto de toda a apresentação, use o método estático [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) exposto pela classe SlideUtil. O código abaixo verifica o texto e as informações de formatação de uma apresentação, incluindo os slides mestres.
{{% blocks/products/pf/agp/code-block title="Extraindo texto da apresentação PPT usando Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Como extrair texto de PPT via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para analisar arquivos PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar PPT com uma instância de Apresentação
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenha uma matriz de objetos TextFrame de todos os slides no PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Percorra a matriz de TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Percorre os parágrafos no TextFrame atual
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Percorrer partes do parágrafo atual
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obter texto na parte atual
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de análise suportados" subTitle="Usando Python, você também pode digitalizar os seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}