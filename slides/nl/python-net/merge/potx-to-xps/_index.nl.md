---
title: Voeg POTX-bestanden samen naar XPS met Python
url: /nl/python-net/merge/potx-to-xps/
keywords: Voeg POTX samen tot XPS, voeg POTX toe aan XPS, combineer POTX tot XPS, PowerPoint, Presentatie, XPS, Python, Aspose
description: Voeg meerdere POTX-bestanden samen in Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Samenvoegen POTX bestanden naar XPS samen in Python" h2="Hoge snelheid en platformonafhankelijke Python API die helpt bij het ontwikkelen van applicaties met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Samenvoegen POTX naar XPS in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om meerdere POTX-presentaties te combineren. Wanneer u de ene presentatie met de andere samenvoegt, combineert u effectief hun dia's in één presentatie om één bestand te verkrijgen. Met Aspose.Slides kunt u twee presentaties op verschillende manieren samenvoegen. U kunt presentaties samenvoegen met al hun vormen, stijlen, teksten, opmaak, opmerkingen, animaties, enz. zonder dat u zich zorgen hoeft te maken over kwaliteitsverlies of gegevens.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Voeg POTX bestanden samen tot XPS met Python" %}}
Om de PowerPoint-presentaties samen te voegen, moet u de dia's van de ene presentatie naar de andere klonen.

{{% blocks/products/pf/agp/code-block title="Python-code voor het samenvoegen van meerdere POTX in een enkel XPS bestand" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.potx") as pres1:
    with slides.Presentation("presentation2.potx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.xps", slides.export.SaveFormat.XPS)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe POTX samen te voegen met XPS met behulp van Aspose.Slides voor Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om twee POTX-bestanden samen te voegen en het resultaat op te slaan als XPS in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/nl/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekverwijzing toe (importeer de bibliotheek) aan uw Python-project.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden POTX in Python.
```
pres1 = slides.Presentation('pres1.potx')
pres2 = slides.Presentation('pres2.potx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combineer POTX bestanden met de methode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla de presentatie op en krijg het resultaat als één XPS bestand.
```
pres1.save("presentation.xps", slides.export.SaveFormat.XPS)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDF-bestanden online samenvoegen" sectionDescription="[PDF samenvoegen in Python](https://products.aspose.com/slides/nl/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Exporteer POTX naar andere ondersteunde formaten" subTitle="U kunt POTX ook combineren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-pptx/" name="POTX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-ppt/" name="POTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-pdf/" name="POTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-html/" name="POTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-png/" name="POTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-bmp/" name="POTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-jpg/" name="POTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-fodp/" name="POTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-gif/" name="POTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-odp/" name="POTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-otp/" name="POTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-pot/" name="POTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-potm/" name="POTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-pps/" name="POTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-ppsm/" name="POTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-ppsx/" name="POTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-pptm/" name="POTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-svg/" name="POTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potx-to-tiff/" name="POTX TO TIFF" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}