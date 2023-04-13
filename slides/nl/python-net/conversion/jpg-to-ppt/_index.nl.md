---
title: Converteer JPG naar PPT in Python
url: /nl/python-net/conversion/jpg-to-ppt/
keywords: Converteer JPG naar PPT, JPG naar PPT, PowerPoint, JPG, PPT, Python API, Python Library
description: Converteer JPG naar PPT in Python. Gebruik de Python-bibliotheek-API om JPG-afbeeldingen naar PowerPoint te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer JPG naar PPT in Python" h2="Krachtige platformonafhankelijke Python API voor het converteren van JPG naar PPT met behulp van Python-code" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer JPG naar PPT met Aspose.Slides" %}}

[**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek die wordt gebruikt om PowerPoint-presentaties, pdf's, HTML-documenten en andere bestanden. Wanneer u JPG naar PPT converteert, maakt u in wezen een PowerPoint-presentatie met dia's op basis van JPG-afbeeldingen.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Converteer JPG naar PPT in Python" %}}
Met behulp van [**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/), kunt u JPG-afbeeldingen converteren naar PowerPoint-presentatie met slechts een paar regels code:

{{% blocks/products/pf/agp/code-block title="Python-code voor het converteren van JPG naar PPT" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hoe JPG naar PPT in Python te converteren" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg de bibliotheek toe als referentie in uw project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van de klasse Presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad de JPG-afbeelding die u naar PPT wilt converteren.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het resulterende bestand op als een PPT-presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis online converter" sectionDescription="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde PowerPoint-conversies" subTitle="U kunt ook bestanden in andere formaten naar PowerPoint converteren" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}