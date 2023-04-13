---
title: Konvertálja a JPG-t PPTX-re Pythonban
url: /hu/python-net/conversion/jpg-to-pptx/
keywords: JPG konvertálása PPTX-re, JPG konvertálása PPTX-re, PowerPoint, JPG, PPTX, Python API, Python Library
description: Konvertálja a JPG-t PPTX-re Pythonban. Használja a Python könyvtár API-t a JPG képek PowerPoint formátumba konvertálásához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertálja a JPG-t PPTX-re Pythonban" h2="Hatékony, többplatformos Python API JPG-ből PPTX-vé konvertálásához Python kóddal" >}}

{{% blocks/products/pf/feature-page-section h2="JPG konvertálása PPTX-re az Aspose.Slides segítségével" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár, amellyel PowerPoint-prezentációkat, PDF-eket, HTML dokumentumokat és egyéb fájlokat. Amikor JPG-t PPTX-re konvertál, lényegében egy PowerPoint-prezentációt hoz létre, amely JPG-képeken alapuló diákat tartalmaz.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JPG-t PPTX-re Pythonban" %}}
Az [**Aspose.Slides for Python .NET-en keresztül**](https://products.aspose.com/slides/hu/python-net/) használatával néhány sornyi kóddal konvertálhatja a JPG képet PowerPoint prezentációvá:

{{% blocks/products/pf/agp/code-block title="Python kód a JPG PPTX-re konvertálásához" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet JPG-t PPTX-re konvertálni a Pythonban" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for Python programot .NET-en keresztül**. Lásd: [**Telepítés**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adja hozzá a könyvtárat referenciaként a projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Prezentáció osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a PPTX formátumba konvertálni kívánt JPG képet.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a kapott fájlt PPTX-prezentációként.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott PowerPoint-konverziók" subTitle="Más formátumú fájlokat is konvertálhat PowerPointba" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}