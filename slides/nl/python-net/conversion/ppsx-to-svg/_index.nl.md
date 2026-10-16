---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PPSX naar SVG in Python
weight: 2170
url: /nl/python-net/conversion/ppsx-to-svg/ 
keywords: "Convert, PowerPoint, PPSX, SVG, Presentation, Python"
description: Voorbeeldcode voor conversie van PPSX naar SVG Python. Gebruik PowerPoint Python API voor batchconversie van PPSX-bestanden naar SVG-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PPSX naar SVG in Python" h2="Krachtige PowerPoint Python-bibliotheek voor het converteren van PPSX naar SVG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PPSX naar SVG in Python" %}}

Wilt u PPSX-bestanden programmatisch naar SVG converteren? Met behulp van [*Aspose.Slides voor Python via .NET*](https://products.aspose.com/slides/nl/python-net/) kan elke ontwikkelaar PPSX converteren naar SVG-indeling met slechts een paar regels Python-code.

Aspose.Slides voor Python is een moderne API voor het verwerken van presentaties en maakt snel SVG van PPSX. Test de kwaliteit van de conversie van PPSX naar SVG rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u PPSX-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [PyPI](https://pypi.org/project/Aspose.Slides/) met behulp van de volgende pip-opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sla PPSX op als SVG in Python" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van PPSX naar SVG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont PPSX naar SVG Python-conversie" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsx") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PPSX naar SVG te converteren in Python" intro="Dit zijn de stappen om een ​​PPSX-bestand naar SVG te converteren met Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad PPSX-bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand en SaveFormat.SVG als parameters specificeert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX-bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="systeem vereisten" intro="Voordat u de broncode van het Python-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." %}}

- Op Microsoft Windows of Linux gebaseerd besturingssysteem (zie [meer](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 of hoger
- Aspose.Slides voor Python waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app om PPSX te converteren naar SVG"
  description="[Probeer onze gratis MP4 To MP3 app](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PPSX ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Verbeterde metabestandsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
