---
title: Extrahieren Sie Text und Bilder aus PPTX-Dateien mit Python
url: /de/python-net/parser/pptx/
keywords: parse PPTX mit Python, PPTX parser Python, extrahiere Daten aus PPTX in Python, extrahiere Text aus PPTX mit Python, extrahiere Bilder aus PPTX mit Python
description: Python-Quellcode zum Analysieren der PPTX-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extrahieren Sie Text und Bilder aus der PPTX-Präsentation mit Python" h2="Erstellen Sie mithilfe serverseitiger APIs Ihre eigenen Python-Apps zum Extrahieren von Text-, Bild-, Video- und Audiodateien aus PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Text aus PPTX-Präsentation über Python extrahieren" %}}
Um den Text der gesamten Präsentation zu scannen, verwenden Sie die statische Methode [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/), die von der SlideUtil-Klasse verfügbar gemacht wird. Der folgende Code scannt den Text und die Formatierungsinformationen aus einer Präsentation, einschließlich der Masterfolien.
{{% blocks/products/pf/agp/code-block title="Extrahieren von Text aus PPTX-Präsentation mit Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="So extrahieren Sie Text aus PPTX über Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Analysieren von PPTX-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPTX mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Holen Sie sich ein Array von TextFrame-Objekten von allen Folien im PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Durchlaufen Sie das Array von TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Absätze im aktuellen TextFrame durchlaufen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Teile im aktuellen Absatz durchlaufen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Holen Sie sich Text im aktuellen Teil
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Parse-Formate" subTitle="Mit Python können Sie auch die folgenden Formate scannen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}