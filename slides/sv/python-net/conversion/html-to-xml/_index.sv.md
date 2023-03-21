---
title: Konvertera HTML till XML i Python
url: /sv/python-net/conversion/html-to-xml/
keywords: HTML till XML, Konvertera HTML till XML, Python API, Python Library, HTML, XML
description: Konvertera HTML till XML i Python. Använd Python library API för att konvertera HTML-filer till XMLs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera HTML till XML i Python" h2="Höghastighets- och plattformsoberoende Python-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera HTML till XML i Python" %}}

[**Aspose.Slides för Python via .NET**](https://products.aspose.com/slides/sv/python-net/) är ett kraftfullt Python-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera HTML till XML. Genom att använda **Aspose.Slides för Python via .NET** kan alla utvecklare eller applikationer konvertera HTML till XML-filer med bara några rader Python-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides for Python snabbt HTML-filer till XML-filformat. Aspose PowerPoint-bibliotek låter dig konvertera HTML till XML och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera HTML till XML med Python" %}}
För att konvertera HTML till XML måste du skapa en presentation från filen HTML och spara den som XML.

{{% blocks/products/pf/agp/code-block title="Python-kod för att konvertera HTML till XML" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open(dataDir + "file.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.xml".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar HTML till XML med Aspose.Slides för Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera HTML till XML i Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/sv/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Python-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna HTML i Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som XML-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis onlinekonverterare" sectionDescription="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera HTML till andra format som stöds" subTitle="Du kan också konvertera HTML och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}