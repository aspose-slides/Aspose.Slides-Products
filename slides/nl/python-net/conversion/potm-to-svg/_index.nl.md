---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer POTM naar SVG in Python
weight: 1290
url: /nl/python-net/conversion/potm-to-svg/ 
keywords: "Convert, PowerPoint, POTM, SVG, Presentation, Python"
description: Voorbeeldcode voor conversie van POTM naar SVG Python. Gebruik PowerPoint Python API voor batchconversie van POTM-bestanden naar SVG-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer POTM naar SVG in Python" h2="Krachtige PowerPoint Python-bibliotheek voor het converteren van POTM naar SVG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer POTM naar SVG in Python" %}}

Wilt u POTM-bestanden programmatisch naar SVG converteren? Met behulp van [*Aspose.Slides voor Python via .NET*](https://products.aspose.com/slides/nl/python-net/) kan elke ontwikkelaar POTM converteren naar SVG-indeling met slechts een paar regels Python-code.

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor Python snel SVG van POTM. Test de kwaliteit van de conversie van POTM naar SVG rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u POTM-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [PyPI](https://pypi.org/project/Aspose.Slides/) met behulp van de volgende pip-opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POTM opslaan als SVG in Python" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van POTM naar SVG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont POTM naar SVG Python-conversie" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potm") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe POTM naar SVG te converteren in Python" intro="Dit zijn de stappen om een ​​POTM-bestand naar SVG te converteren met Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad POTM-bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand en SaveFormat.SVG als parameters specificeert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POTM-bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="systeem vereisten" intro="Voordat u de broncode van het Python-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." %}}

- Op Microsoft Windows of Linux gebaseerd besturingssysteem (zie [meer](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 of hoger
- Aspose.Slides voor Python waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app om POTM te converteren naar SVG"
  description="[Probeer onze gratis Collage app](https://products.aspose.app/slides/collage/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt POTM ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-emf/" name="POTM TO EMF" description="Verbeterde metabestandsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-gif/" name="POTM TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-html/" name="POTM TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-jpg/" name="POTM TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocument-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-otp/" name="POTM TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-pdf/" name="POTM TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-png/" name="POTM TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/potm-to-xps/" name="POTM TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
