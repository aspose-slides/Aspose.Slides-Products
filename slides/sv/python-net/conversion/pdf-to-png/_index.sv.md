---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PDF till PNG i Python
url: /sv/python-net/conversion/pdf-to-png/
keywords: PDF till PNG, Konvertera PDF till PNG, Python API, Python Library, PDF, PNG
description: Konvertera PDF till PNG i Python. Använd Python library API för att konvertera PDF-filer till PNGs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PDF till PNG i Python" h2="Höghastighets- och plattformsoberoende Python-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PDF till PNG med Python" variant="code" %}}

För att konvertera PDF till PNG måste du skapa en presentation från filen PDF och spara den som PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python-kod för att konvertera PDF till PNG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing
        
with slides.Presentation() as pres:
    pres.slides.add_from_pdf("document.pdf")
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PDF till PNG i Python" %}}

[**Aspose.Slides för Python via .NET**](https://products.aspose.com/slides/sv/python-net/) är ett kraftfullt Python-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera PDF till PNG. Genom att använda **Aspose.Slides för Python via .NET** kan alla utvecklare eller applikationer konvertera PDF till PNG-filer med bara några rader Python-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides for Python snabbt PDF-filer till PNG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera PDF till PNG och många andra filformat

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar PDF till PNG med Aspose.Slides för Python API" intro="Det här är stegen för att konvertera PDF till PNG i Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/sv/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en biblioteksreferens (importera biblioteket) till ditt Python-projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna källfilerna PDF i Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara resultatet som PNG-fil.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis onlinekonverterare"
  description="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertera PDF till andra format som stöds" subTitle="Du kan också konvertera PDF och spara till andra filformat. Se alla format som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
