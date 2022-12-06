---
title: Voeg SVG samen met PNG in Python
url: /nl/python-net/merge/svg-to-png/
keywords: Voeg SVG naar PNG, SVG naar PNG, Join SVG naar PNG, Combineer SVG naar PNG, Python API, Python Library
description: Voeg SVG samen met PNG in Python. Gebruik de Python-bibliotheek-API om SVG- en PNG-bestanden te combineren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Voeg SVG samen met PNG in Python" h2="Snelle en platformonafhankelijke Python-bibliotheek voor het samenvoegen van SVG naar PNG-afbeeldingen met behulp van Python-code" >}}

{{% blocks/products/pf/feature-page-section h2="Voeg SVG samen met PNG met behulp van Aspose.Slides" %}}

[**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek die wordt gebruikt om presentaties, afbeeldingen en andere bestanden samen te voegen en te manipuleren. Wanneer u SVG naar PNG samenvoegt, combineert u in feite SVG-afbeeldingen om een ​​PNG-afbeelding te krijgen.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Voeg SVG samen met PNG in Python" %}}
Met behulp van [**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/), kunt u snel SVG-bestanden samenvoegen in PNG-bestanden met slechts een paar regels code

{{% blocks/products/pf/agp/code-block title="Python-code voor het samenvoegen van SVG naar PNG" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)

    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hoe SVG naar PNG in Python samen te voegen" >}}


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
Laad de SVG-bestanden die u wilt samenvoegen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla de resulterende PNG-afbeelding op.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Andere bestanden samenvoegen" subTitle="Je kunt ook bestanden in andere formaten combineren om een ​​enkel bestand te krijgen" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}