---
title: Extrahujte text a obrázky ze souborů ODP pomocí Python
url: /cs/python-net/parser/odp/
keywords: analyzovat ODP pomocí Python, ODP analyzátor Python, extrahovat data z ODP v Python, extrahovat text z ODP pomocí Python, extrahovat obrázky z ODP pomocí Python
description: Zdrojový kód Python k analýze prezentace ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extrahujte text a obrázky z prezentace ODP pomocí Python" h2="Vytvořte si vlastní aplikace pro Python pro extrahování textových, obrazových, video a zvukových souborů z PowerPointu pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Extrahujte text z prezentace ODP prostřednictvím Python" %}}
Chcete-li naskenovat text z celé prezentace, použijte statickou metodu [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) vystavenou třídou SlideUtil. Níže uvedený kód naskenuje text a informace o formátování z prezentace, včetně hlavních snímků.
{{% blocks/products/pf/agp/code-block title="Extrahování textu z prezentace ODP pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a ODP file
with slides.Presentation("pres.odp") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the ODP
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

{{< blocks/products/pf/feature-page-section  h2="Jak extrahovat text z ODP přes Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k analýze souborů ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte ODP s instancí Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Získejte pole objektů TextFrame ze všech snímků ve ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Procházejte polem TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Procházet odstavce v aktuálním TextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Procházejte části v aktuálním odstavci
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Získejte text v aktuální části
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty analýzy" subTitle="Pomocí Python můžete také skenovat následující formáty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}