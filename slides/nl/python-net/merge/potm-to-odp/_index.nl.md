---
title: Voeg POTM-bestanden samen naar ODP met Python
url: /nl/python-net/merge/potm-to-odp/
keywords: Voeg POTM samen tot ODP, voeg POTM toe aan ODP, combineer POTM tot ODP, PowerPoint, Presentatie, ODP, Python, Aspose
description: Voeg meerdere POTM-bestanden samen in Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Samenvoegen POTM bestanden naar ODP samen in Python" h2="Hoge snelheid en platformonafhankelijke Python API die helpt bij het ontwikkelen van applicaties met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Samenvoegen POTM naar ODP in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/nl/python-net/) is een krachtige Python-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om meerdere POTM-presentaties te combineren. Wanneer u de ene presentatie met de andere samenvoegt, combineert u effectief hun dia's in één presentatie om één bestand te verkrijgen. Met Aspose.Slides kunt u twee presentaties op verschillende manieren samenvoegen. U kunt presentaties samenvoegen met al hun vormen, stijlen, teksten, opmaak, opmerkingen, animaties, enz. zonder dat u zich zorgen hoeft te maken over kwaliteitsverlies of gegevens.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Voeg POTM bestanden samen tot ODP met Python" %}}
Om de PowerPoint-presentaties samen te voegen, moet u de dia's van de ene presentatie naar de andere klonen.

{{% blocks/products/pf/agp/code-block title="Python-code voor het samenvoegen van meerdere POTM in een enkel ODP bestand" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.potm") as pres1:
    with slides.Presentation("presentation2.potm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe POTM samen te voegen met ODP met behulp van Aspose.Slides voor Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om twee POTM-bestanden samen te voegen en het resultaat op te slaan als ODP in Python." >}}

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
Open de bronbestanden POTM in Python.
```
pres1 = slides.Presentation('pres1.potm')
pres2 = slides.Presentation('pres2.potm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combineer POTM bestanden met de methode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla de presentatie op en krijg het resultaat als één ODP bestand.
```
pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exporteer POTM naar andere ondersteunde formaten" subTitle="U kunt POTM ook combineren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-pptx/" name="POTM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-ppt/" name="POTM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-pdf/" name="POTM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-html/" name="POTM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-png/" name="POTM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-bmp/" name="POTM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-jpg/" name="POTM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-fodp/" name="POTM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-gif/" name="POTM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-otp/" name="POTM TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-pot/" name="POTM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-potx/" name="POTM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-pps/" name="POTM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-ppsm/" name="POTM TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-ppsx/" name="POTM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-pptm/" name="POTM TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-svg/" name="POTM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-tiff/" name="POTM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/merge/potm-to-xps/" name="POTM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}