---
title: Estrai testo e immagini da file PPTX utilizzando Python
url: /it/python-net/parser/pptx/
keywords: analizza PPTX utilizzando Python, PPTX parser Python, estrai dati da PPTX in Python, estrai testo da PPTX utilizzando Python, estrai immagini da PPTX utilizzando Python
description: Python codice sorgente per analizzare la presentazione PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Estrai testo e immagini dalla presentazione in PPTX utilizzando Python" h2="Crea le tue app Python per estrarre file di testo, immagini, video e audio da PowerPoint utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Estrai il testo dalla presentazione in PPTX tramite Python" %}}
Per eseguire la scansione del testo dell'intera presentazione, utilizza il metodo statico [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) esposto dalla classe SlideUtil. Il codice seguente esegue la scansione del testo e delle informazioni di formattazione da una presentazione, incluse le diapositive master.
{{% blocks/products/pf/agp/code-block title="Estrazione del testo dalla presentazione PPTX utilizzando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPTX file
with slides.Presentation("pres.pptx") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPTX
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

{{< blocks/products/pf/feature-page-section  h2="Come estrarre il testo da PPTX tramite Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per analizzare i file PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPTX con un'istanza di Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ottieni una matrice di oggetti TextFrame da tutte le diapositive in PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Passa attraverso l'array di TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Passa attraverso i paragrafi nel TextFrame corrente
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Passa attraverso le parti nel paragrafo corrente
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ottieni il testo nella parte corrente
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di analisi supportati" subTitle="Utilizzando Python, puoi anche scansionare i seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}