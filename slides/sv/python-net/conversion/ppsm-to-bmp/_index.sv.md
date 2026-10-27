---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPSM till BMP i Python
weight: 1770
url: /sv/python-net/conversion/ppsm-to-bmp/ 
keywords: "Convert, PowerPoint, PPSM, BMP, Presentation, Python"
description: Exempelkod för konvertering från PPSM till BMP Python. Använd PowerPoint Python API för batchkonvertering av PPSM-filer till BMP-filer.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPSM till BMP i Python" h2="Kraftfullt PowerPoint Python-bibliotek för att konvertera PPSM till BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PPSM till BMP i Python" %}}

Behöver du konvertera PPSM-filer till BMP programmatiskt? Genom att använda [*Aspose.Slides för Python via .NET*](https://products.aspose.com/slides/sv/python-net/) kan alla utvecklare konvertera PPSM till BMP-format med bara några rader Python-kod.

Som ett modernt presentationsbearbetnings-API skapar Aspose.Slides för Python BMP från PPSM snabbt. Testa kvaliteten på PPSM till BMP-konvertering direkt i din [webbläsare](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX-bibliotek låter dig konvertera PPSM-filer till många populära format.

Du kan installera biblioteket från [PyPI](https://pypi.org/project/Aspose.Slides/) med följande pip-kommando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Spara PPSM som BMP i Python" %}}

Använd gratisappen för att se en demonstration av PPSM till BMP-konverteringsprocessen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Denna exempelkod visar PPSM till BMP Python-konvertering" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar PPSM till BMP i Python" intro="Det här är stegen för att konvertera en PPSM-fil till BMP med Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda PPSM-fil med en instans av presentationsklassen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `spara`-metoden samtidigt som du anger sökvägen till utdatafilen och SaveFormat.BMP som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSM-filen kommer att sparas på den angivna sökvägen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Innan du kör källkoden för Python-konverteringsexemplet, se till att du har följande förutsättningar." %}}

- Microsoft Windows eller Linux-baserat operativsystem (se [mer](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 eller senare
- Aspose.Slides för Python som refereras till i ditt projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Byggd med Aspose.Slides" title="Konvertera PPSM till BMP online" description="Den kostnadsfria appen Aspose.Slides Conversion är byggd med [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/sv/python-net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPSM-filer." button="Öppna Aspose.Slides Conversion" note="[Alla gratisappar](https://products.aspose.app/slides/family)" upload="Släpp eller ladda upp din fil" saveAs="Spara som" convert="Konvertera" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides konverterar filer innan du skriver kod.
- Ladda upp PPSM-filer och spara dem som BMP.
- Ladda ned resultatet eller konvertera fler filer.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPSM till många andra filformat. Se andra omvandlingar som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Förbättrat metafilformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocument platt XML-presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Grafiskt utbytesformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="JPEG-bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Portabelt dokumentformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Bärbar nätverksgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint-mallfiler" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint-mallfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Makroaktiverad presentationsfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Öppna XML-presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Skalbar vektorgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWF-format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Taggad bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
