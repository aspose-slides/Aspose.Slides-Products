---
title: Konvertálja a képet PPTX-re Pythonban
url: /hu/python-net/conversion/image-to-pptx/
keywords: Kép PPTX-be, Kép konvertálása PPTX-be, Python API, Python Library, Image, PPTX
description: Konvertálja a képet PPTX-re Pythonban. Használja Python könyvtár API-t a képfájlok PDF formátumba konvertálásához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertálja a képet PPTX-re Pythonban" h2="Nagy sebességű és többplatformos Python Library, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a képet PPTX-re Pythonban" %}}

Az [**Aspose.Slides for Python .NET-en keresztül**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a kép PPTX-re konvertálására. Az **Aspose.Slides for Python .NET-en keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a képeket PPTX-fájlokká, mindössze néhány soros Python-kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Python gyorsan exportálja a képfájlokat PPTX fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a kép konvertálását PDF formátumba és sok más fájlformátumba

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a képet PPTX-re Python segítségével" %}}
A kép PPTX-re konvertálásához létre kell hoznia egy prezentációt a képfájlból, és el kell mentenie PPTX-ként.

{{% blocks/products/pf/agp/code-block title="Python kód a kép PPTX-vé konvertálásához" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.pptx", slides.export.SaveFormat.PPTX)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Kép konvertálása PPTX-re az Aspose.Slides for Python API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a kép PPTX-re konvertálásához Pythonban." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Python-projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrásképfájlokat a Pythonban.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPTX fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Kép konvertálása más támogatott formátumokba" subTitle="A képeket konvertálhatja és más fájlformátumokba is mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}