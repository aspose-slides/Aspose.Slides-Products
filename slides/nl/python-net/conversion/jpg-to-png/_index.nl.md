---
title: Converteer JPG naar PNG in Python
url: /nl/python-net/conversion/jpg-to-png/
keywords: JPG naar PNG, Converteer JPG naar PNG, Python API, Python Library, JPG, PNG
description: Converteer JPG naar PNG in Python. Gebruik de Python-bibliotheek-API om JPG-bestanden naar PNG-bestanden te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer JPG naar PNG in Python" h2="Snelle en platformonafhankelijke Python-bibliotheek die helpt bij het ontwikkelen van applicaties met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer JPG naar PNG in Python" %}}

[**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om JPG naar PNG te converteren. Met behulp van **Aspose.Slides voor Python via .NET** kan elke ontwikkelaar of toepassing JPG naar PNG bestanden converteren met slechts een paar regels Python-code.

Aspose.Slides voor Python is een moderne documentverwerkings-API en exporteert snel JPG-bestanden naar PNG-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u JPG naar PNGs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer JPG naar PNG met behulp van Python" %}}
Om de JPG naar PNG te converteren, moet u een presentatie maken van het JPG-bestand en deze opslaan als PNG.

{{% blocks/products/pf/agp/code-block title="Python-code voor het converteren van JPG naar PNG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe JPG naar PNG te converteren met Aspose.Slides voor Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om JPG naar PNG te converteren in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/nl/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekverwijzing toe (importeer de bibliotheek) aan uw Python-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden JPG in Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op als PNG bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis online converter" sectionDescription="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer JPG naar andere ondersteunde formaten" subTitle="U kunt JPG ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}