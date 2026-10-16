---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PPSM naar PNG in Python
weight: 1860
url: /nl/python-net/conversion/ppsm-to-png/ 
keywords: "Convert, PowerPoint, PPSM, PNG, Presentation, Python"
description: Voorbeeldcode voor conversie van PPSM naar PNG Python. Gebruik PowerPoint Python API voor batchconversie van PPSM-bestanden naar PNG-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PPSM naar PNG in Python" h2="Krachtige PowerPoint Python-bibliotheek voor het converteren van PPSM naar PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PPSM naar PNG in Python" %}}

Wilt u PPSM-bestanden programmatisch naar PNG converteren? Met behulp van [*Aspose.Slides voor Python via .NET*](https://products.aspose.com/slides/nl/python-net/) kan elke ontwikkelaar PPSM naar PNG-indeling converteren met slechts een paar regels Python-code.

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor Python snel PNG van PPSM. Test de kwaliteit van de conversie van PPSM naar PNG rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion/ppt-to-png). Met de Aspose PowerPoint PPTX-bibliotheek kunt u PPSM-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [PyPI](https://pypi.org/project/Aspose.Slides/) met behulp van de volgende pip-opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sla PPSM op als PNG in Python" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van PPSM naar PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont PPSM naar PNG Python-conversie" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PPSM naar PNG in Python te converteren?" intro="Dit zijn de stappen om een ​​PPSM-bestand naar PNG te converteren met Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad PPSM-bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand & SaveFormat.PNG als parameters opgeeft{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSM-bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="systeem vereisten" intro="Voordat u de broncode van het Python-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." %}}

- Op Microsoft Windows of Linux gebaseerd besturingssysteem (zie [meer](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 of hoger
- Aspose.Slides voor Python waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app om PPSM te converteren naar PNG"
  description="[Probeer onze gratis app om PPT te converteren naar PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PPSM ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Verbeterde metabestandsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Schaalbare vectorafbeeldingen" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
