---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera FODP till BMP i Python
weight: 10
url: /sv/python-net/conversion/fodp-to-bmp/ 
keywords: "Convert, PowerPoint, FODP, BMP, Presentation, Python"
description: Exempelkod för FODP till BMP Python-konvertering. Använd PowerPoint Python API för batchkonvertering av FODP-filer till BMP-filer.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera FODP till BMP i Python" h2="Kraftfullt PowerPoint Python-bibliotek för att konvertera FODP till BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera FODP till BMP i Python" %}}

Behöver du konvertera FODP-filer till BMP programmatiskt? Genom att använda [*Aspose.Slides för Python via .NET*](https://products.aspose.com/slides/sv/python-net/) kan vilken utvecklare som helst konvertera FODP till BMP-format med bara några rader Python-kod.

Som ett modernt presentationsbearbetnings-API skapar Aspose.Slides för Python BMP från FODP snabbt. Testa kvaliteten på FODP till BMP-konvertering direkt i din [webbläsare](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX-bibliotek låter dig konvertera FODP-filer till många populära format.

Du kan installera biblioteket från [PyPI](https://pypi.org/project/Aspose.Slides/) med följande pip-kommando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Spara FODP som BMP i Python" %}}

Använd gratisappen för att se en demonstration av FODP till BMP-konverteringsprocessen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Denna exempelkod visar FODP till BMP Python-konvertering" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar FODP till BMP i Python" intro="Det här är stegen för att konvertera en FODP-fil till BMP med Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda FODP-fil med en instans av klassen Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `spara`-metoden samtidigt som du anger sökvägen till utdatafilen och SaveFormat.BMP som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FODP-filen kommer att sparas på den angivna sökvägen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Innan du kör källkoden för Python-konverteringsexemplet, se till att du har följande förutsättningar." %}}

- Microsoft Windows eller Linux-baserat operativsystem (se [mer](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 eller senare
- Aspose.Slides för Python som refereras till i ditt projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app att konvertera FODP till BMP"
  description="[Prova vår gratis Editor -app](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera FODP till många andra filformat. Se andra omvandlingar som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-emf/" name="FODP TO EMF" description="Förbättrat metafilformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafiskt utbytesformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG-bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Portabelt dokumentformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="Bärbar nätverksgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="Microsoft PowerPoint-mallfiler" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint-mallfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Makroaktiverat bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Makroaktiverad presentationsfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Öppna XML-presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-svg/" name="FODP TO SVG" description="Skalbar vektorgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF-format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Taggad bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
