---
title: Extraheer tekst en afbeeldingen uit PPTX-bestanden met behulp van Python
url: /nl/python-net/parser/pptx/
keywords: ontleed PPTX met Python, PPTX ontleder Python, extraheer gegevens uit PPTX in Python, extraheer tekst uit PPTX met Python, extraheer afbeeldingen uit PPTX met Python
description: Python broncode om PPTX presentatie te ontleden.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extraheer tekst en afbeeldingen uit PPTX presentatie met behulp van Python" h2="Bouw uw eigen Python-apps voor het extraheren van tekst-, beeld-, video- en audiobestanden uit PowerPoint met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Extraheer tekst uit PPTX presentatie via Python" %}}
Gebruik de statische methode [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) die wordt weergegeven door de klasse SlideUtil om de tekst van de hele presentatie te scannen. De onderstaande code scant de tekst en opmaakinformatie van een presentatie, inclusief de basisdia's.
{{% blocks/products/pf/agp/code-block title="Tekst extraheren uit PPTX-presentatie met behulp van Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Tekst extraheren uit PPTX via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PPTX bestanden te parseren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPTX met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Krijg een reeks TextFrame-objecten van alle dia's in de PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop door de array van TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Doorloop alinea's in het huidige TextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Doorloop gedeelten in de huidige alinea
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Krijg tekst in het huidige gedeelte
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde ontleedformaten" subTitle="Met Python kunt u ook de volgende formaten scannen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}