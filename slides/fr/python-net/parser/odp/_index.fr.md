---
title: Extrayez du texte et des images à partir de fichiers ODP à l'aide de Python
url: /fr/python-net/parser/odp/
keywords: analysez ODP en utilisant Python, analysez ODP Python, extrayez des données de ODP en Python, extrayez du texte de ODP en utilisant Python, extrayez des images de ODP en utilisant Python
description: Code source Python pour analyser la présentation ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extraire le texte et les images de la présentation ODP à l'aide de Python" h2="Créez vos propres applications Python pour extraire des fichiers texte, image, vidéo et audio de PowerPoint à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Extraire le texte de la présentation ODP via Python" %}}
Pour analyser le texte de toute la présentation, utilisez la méthode statique [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) exposée par la classe SlideUtil. Le code ci-dessous analyse le texte et les informations de mise en forme d'une présentation, y compris les diapositives principales.
{{% blocks/products/pf/agp/code-block title="Extraction de texte de la présentation ODP à l'aide de Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Comment extraire du texte de ODP via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour analyser les fichiers ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger ODP avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenez un tableau d'objets TextFrame de toutes les diapositives dans le ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Boucle à travers le tableau de TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Boucle à travers les paragraphes dans le TextFrame actuel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Boucle sur des parties du paragraphe actuel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenir du texte dans la partie actuelle
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats d'analyse pris en charge" subTitle="À l'aide de Python, vous pouvez également numériser les formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}