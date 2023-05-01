---
title: Szöveg és képek kibontása a PPTX fájlokból a Python használatával
url: /hu/python-net/parser/pptx/
keywords: elemezze a PPTX elemet a Python használatával, a PPTX elemzőt a Python használatával, kinyerje ki az adatokat a PPTX elemből a Python nyelven, bontsa ki a szöveget a PPTX-ből a Python használatával, bontsa ki a képeket a PPTX-ból a Python használatával
description: Python forráskód a PPTX prezentáció elemzéséhez.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Szöveg és képek kibontása a PPTX prezentációból a Python használatával" h2="Készítse el saját Python-alkalmazásait a szöveg-, kép-, video- és hangfájlok PowerPointból való kinyeréséhez szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Szöveg kibontása a PPTX prezentációból a Python segítségével" %}}
A teljes prezentáció szövegének beolvasásához használja a [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) statikus metódust, amelyet a SlideUtil osztály tesz közzé. Az alábbi kód beolvassa a szöveget és a formázási információkat egy prezentációból, beleértve a fődiákat is.
{{% blocks/products/pf/agp/code-block title="Szöveg kinyerése a PPTX prezentációból a Python használatával" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Szöveg kinyerése a PPTX formátumból a Python segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PPTX fájlok elemzéséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPTX betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Szerezzen le egy TextFrame objektumtömböt a PPTX összes diájáról
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lapozzon át a TextFrames tömbön
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lapozás a bekezdések között az aktuális szövegkeretben
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lapozzon át a részeken az aktuális bekezdésben
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Szöveg lekérése az aktuális részben
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott elemzési formátumok" subTitle="A Python használatával a következő formátumokat is beolvashatja:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}