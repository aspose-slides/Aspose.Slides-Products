---
title: Bild mit BMP in Python zusammenführen
url: /de/python-net/merge/image-to-bmp/
keywords: Bild zu BMP, Bild zu BMP zusammenführen, Bild zu BMP verbinden, Bilder kombinieren, Bild, BMP, Python-API, Python-Bibliothek
description: Bild mit BMP in Python zusammenführen. Verwenden Sie die Python-Bibliotheks-API, um Bilder zu kombinieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bild mit BMP in Python zusammenführen" h2="Hochgeschwindigkeits- und plattformübergreifende Python-Bibliothek zum Zusammenführen von Bildern mit BMP-Dateien mithilfe von Python-Code" >}}

{{% blocks/products/pf/feature-page-section h2="Bild mit Aspose.Slides in BMP zusammenführen" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/) ist eine leistungsstarke Python-Bibliothek zum Erstellen, Konvertieren, Zusammenführen und Bearbeiten von Präsentationen und PDFs , Bilder und andere Dateien. Wenn Sie Bilder mit BMP zusammenführen, kombinieren Sie effektiv Bilder, um eine einzelne BMP-Datei zu erhalten.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Bild mit BMP in Python zusammenführen" %}}
Mit [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/) können Sie Bilder mit nur wenigen Codezeilen schnell mit BMP zusammenführen

{{% blocks/products/pf/agp/code-block title="Python-Code zum Zusammenführen von Bild mit BMP" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image1 = pres.images.add_image(drawing.Bitmap("image1.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 100, 100, image1)

    image2 = pres.images.add_image(drawing.Bitmap("image2.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 200, 100, 100, image2)

    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.bmp".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.bmp)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So führen Sie ein Bild mit BMP in Python zusammen" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die Bilder, die Sie zusammenfügen möchten, als Bilderrahmen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die resultierende BMP-Datei.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Andere Dateien zusammenführen" subTitle="Sie können auch Dateien in anderen Formaten kombinieren, um eine einzige Datei zu erhalten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}