---
title: Extrahera text och bilder från PPTX-filer med Python
url: /sv/python-net/parser/pptx/
keywords: analysera PPTX med Python, PPTX parser Python, extrahera data från PPTX i Python, extrahera text från PPTX med Python, extrahera bilder från PPTX med Python
description: Python källkod för att analysera PPTX Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extrahera text och bilder från presentationen PPTX med Python" h2="Bygg dina egna Python-appar för att extrahera text-, bild-, video- och ljudfiler från PowerPoint med API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Extrahera text från PPTX presentation via Python" %}}
För att skanna texten från hela presentationen, använd den statiska metoden [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) som exponeras av SlideUtil-klassen. Koden nedan skannar text- och formateringsinformation från en presentation, inklusive huvudbilderna.
{{% blocks/products/pf/agp/code-block title="Extrahera text från PPTX presentation med Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Så här extraherar du text från PPTX via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att analysera PPTX-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPTX med en instans av Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Få en uppsättning TextFrame-objekt från alla bilder i PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gå igenom arrayen av textramar
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gå igenom stycken i nuvarande TextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gå igenom delar i det aktuella stycket
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hämta text i den aktuella delen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra parseformat som stöds" subTitle="Med Python kan du även skanna följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}