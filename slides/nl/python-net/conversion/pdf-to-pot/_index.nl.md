---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PDF naar POT in Python
weight: 760
url: /nl/python-net/conversion/pdf-to-pot/ 
keywords: "Convert, PowerPoint, PDF, POT, Presentation, Python"
description: Voorbeeldcode voor conversie van PDF naar POT Python. Gebruik PowerPoint Python API voor batchconversie van PDF-bestanden naar POT-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PDF naar POT in Python" h2="Krachtige PowerPoint Python-bibliotheek voor het converteren van PDF naar POT"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PDF naar POT in Python" %}}

Wilt u PDF-bestanden programmatisch naar POT converteren? Met behulp van [*Aspose.Slides voor Python via .NET*](https://products.aspose.com/slides/nl/python-net/) kan elke ontwikkelaar PDF naar POT-indeling converteren met slechts een paar regels Python-code.

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor Python snel POT vanuit PDF. Test de kwaliteit van de conversie van PDF naar POT rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u PDF-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [PyPI](https://pypi.org/project/Aspose.Slides/) met behulp van de volgende pip-opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF opslaan als POT in Python" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van PDF naar POT.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont PDF naar POT Python-conversie" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.pot", slides.export.SaveFormat.POT)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PDF naar POT te converteren in Python" intro="Dit zijn de stappen om een ​​PDF-bestand naar POT te converteren met Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad PDF-bestand met een exemplaar van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand & SaveFormat.POT opgeeft als parameters{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF-bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="systeem vereisten" intro="Voordat u de broncode van het Python-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." %}}

- Op Microsoft Windows of Linux gebaseerd besturingssysteem (zie [meer](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 of hoger
- Aspose.Slides voor Python waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app om PDF te converteren naar POT"
  description="[Probeer onze gratis app om PDF te converteren naar POT](https://products.aspose.app/slides/import/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PDF ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="Verbeterde metabestandsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="OpenDocument-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="Schaalbare vectorafbeeldingen" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
