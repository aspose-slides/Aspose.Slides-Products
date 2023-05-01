---
title: Wyodrębnij tekst i obrazy z plików PPT za pomocą Python
url: /pl/python-net/parser/ppt/
keywords: przeanalizuj PPT za pomocą Python, PPT parser Python, wyodrębnij dane z PPT w Python, wyodrębnij tekst z PPT za pomocą Python, wyodrębnij obrazy z PPT za pomocą Python
description: Python kod źródłowy do analizowania prezentacji PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wyodrębnij tekst i obrazy z prezentacji PPT za pomocą Python" h2="Twórz własne aplikacje Python do wyodrębniania plików tekstowych, obrazów, wideo i audio z programu PowerPoint przy użyciu interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Wyodrębnij tekst z PPT prezentacji przez Python" %}}
Aby zeskanować tekst z całej prezentacji, użyj metody statycznej [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) udostępnionej przez klasę SlideUtil. Poniższy kod skanuje tekst i informacje o formatowaniu z prezentacji, w tym ze slajdów wzorcowych.
{{% blocks/products/pf/agp/code-block title="Wyodrębnianie tekstu z prezentacji PPT za pomocą Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Jak wyodrębnić tekst z PPT przez Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przeanalizować pliki PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPT z instancją Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pobierz tablicę obiektów TextFrame ze wszystkich slajdów w PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapętlanie tablicy ramek tekstowych
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapętlaj akapity w bieżącej ramce TextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapętlaj fragmenty bieżącego akapitu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pobierz tekst w bieżącej części
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty analizy" subTitle="Korzystając z Python, możesz również skanować następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}