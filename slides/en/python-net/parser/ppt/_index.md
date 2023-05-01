---
title: Extract Text and Images from PPT Files using Python
url: /python-net/parser/ppt/
keywords: parse PPT using Python, PPT parser Python, extract data from PPT in Python, extract text from PPT using Python, extract images from PPT using Python 
description: Python source code to parse PPT Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extract Text and Images from PPT presentation using Python" h2="Build your own Python apps for extracting text, image, video and audio files from PowerPoint using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Extract Text from PPT Presentation via Python" %}}
To scan the text from the whole presentation, use the [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) static method exposed by the SlideUtil class. The code below scans the text and formatting information from a presentation, including the master slides.
{{% blocks/products/pf/agp/code-block title="Extracting Text from PPT Presentation using Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="How to Extract Text from PPT via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to Parse PPT files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPT with an instance of Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Get an Array of TextFrame objects from all slides in the PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop through the Array of TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop through paragraphs in current TextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop through portions in the current Paragraph
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Get text in the current portion
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Parse Formats" subTitle="Using Python, You can also scan the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}