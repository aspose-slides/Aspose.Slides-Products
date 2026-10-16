---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PNG in SVG in Python
url: /de/python-net/conversion/png-to-svg/
keywords: PNG in SVG, Konvertiere PNG in SVG, Python-API, Python-Bibliothek, PNG, SVG
description: Konvertieren Sie PNG in SVG in Python. Verwenden Sie die Python-Bibliotheks-API, um PNG-Dateien in SVGs zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PNG in SVG in Python" h2="Hochgeschwindigkeits- und plattformübergreifende Python-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie mit Python PNG in SVG" variant="code" %}}

Um das PNG in SVG zu konvertieren, müssen Sie eine Präsentation aus der PNG-Datei erstellen und sie als SVG speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python-Code zum Konvertieren von PNG in SVG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PNG in SVG in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/) ist eine leistungsstarke Python-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, PNG in SVG zu konvertieren. Mit **Aspose.Slides for Python via .NET** kann jeder Entwickler oder jede Anwendung PNG-Dateien mit nur wenigen Zeilen Python-Code in SVG-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für Python schnell PNG-Dateien in SVG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie PNG in SVGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PNG in SVG mit Aspose.Slides for Python API" intro="Dies sind die Schritte zum Konvertieren von PNG in SVG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie Ihrem Python-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die Quelldateien PNG in Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ergebnis als SVG-Datei speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Kostenloser Online-Konverter"
  description="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertieren Sie PNG in andere unterstützte Formate" subTitle="Sie können PNG auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
