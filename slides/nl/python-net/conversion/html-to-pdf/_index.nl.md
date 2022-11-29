---
title: Converteer HTML naar PDF in Python
url: /nl/python-net/conversion/html-to-pdf/
keywords: HTML naar PDF, Converteer HTML naar PDF, Python API, Python Library, HTML, PDF
description: Converteer HTML naar PDF in Python. Gebruik de Python-bibliotheek-API om HTML-bestanden naar PDF-bestanden te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer HTML naar PDF in Python" h2="Snelle en platformonafhankelijke Python-bibliotheek die helpt bij het ontwikkelen van applicaties met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer HTML naar PDF in Python" %}}

[**Aspose.Slides voor Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om HTML naar PDF te converteren. Met behulp van **Aspose.Slides voor Python via .NET** kan elke ontwikkelaar of toepassing HTML naar PDF bestanden converteren met slechts een paar regels Python-code.

Aspose.Slides voor Python is een moderne documentverwerkings-API en exporteert snel HTML-bestanden naar PDF-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u HTML naar PDFs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer HTML naar PDF met behulp van Python" %}}
Om de HTML naar PDF te converteren, moet u een presentatie maken van het HTML-bestand en deze opslaan als PDF.

{{% blocks/products/pf/agp/code-block title="Python-code voor het converteren van HTML naar PDF" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open(dataDir + "file.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe HTML naar PDF te converteren met Aspose.Slides voor Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om HTML naar PDF te converteren in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/nl/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekverwijzing toe (importeer de bibliotheek) aan uw Python-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden HTML in Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op als PDF bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer HTML naar andere ondersteunde formaten" subTitle="U kunt HTML ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}