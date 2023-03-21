---
title: Converteer JPG naar PDF in Python
url: /nl/python-net/conversion/jpg-to-pdf/
keywords: JPG naar PDF, Converteer JPG naar PDF, Python API, Python Library, JPG, PDF
description: Converteer JPG naar PDF in Python. Gebruik de Python-bibliotheek-API om JPG-bestanden naar PDF-bestanden te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer JPG naar PDF in Python" h2="Snelle en platformonafhankelijke Python-bibliotheek die helpt bij het ontwikkelen van applicaties met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer JPG naar PDF in Python" %}}

[**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om JPG naar PDF te converteren. Met behulp van **Aspose.Slides voor Python via .NET** kan elke ontwikkelaar of toepassing JPG naar PDF bestanden converteren met slechts een paar regels Python-code.

Aspose.Slides voor Python is een moderne documentverwerkings-API en exporteert snel JPG-bestanden naar PDF-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u JPG naar PDFs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer JPG naar PDF met behulp van Python" %}}
Om de JPG naar PDF te converteren, moet u een presentatie maken van het JPG-bestand en deze opslaan als PDF.

{{% blocks/products/pf/agp/code-block title="Python-code voor het converteren van JPG naar PDF" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe JPG naar PDF te converteren met Aspose.Slides voor Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om JPG naar PDF te converteren in Python." >}}

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
Sla resultaat op als PDF bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis online converter" sectionDescription="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer JPG naar andere ondersteunde formaten" subTitle="U kunt JPG ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}