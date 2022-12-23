---
title: PDF szerkesztése Pythonban
url: /hu/python-net/editor/pdf/
keywords: PDF, PDF, Python API, Python Library szerkesztése
description: PDF szerkesztése Pythonban. Használja Python könyvtár API-t a PDF-dokumentum szerkesztéséhez
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PDF szerkesztése Pythonban" h2="Nagy sebességű és többplatformos Python-könyvtár PDF-szerkesztéshez Python-kóddal" >}}

{{% blocks/products/pf/feature-page-section h2="PDF szerkesztése az Aspose.Slides segítségével" %}}

[**Aspose.Slides for Python .NET-en keresztül**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár, amellyel prezentációkat, PDF-dokumentumokat és egyéb fájlokat kezelhet és szerkeszthet. . A PDF-dokumentumot úgy szerkesztheti, hogy új szövegsort ad hozzá. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PDF szerkesztése Pythonban" %}}
Az [**Aspose.Slides for Python .NET-en keresztül**](https://products.aspose.com/slides/hu/python-net/) használatával új szövegsort adhat egy PDF-dokumentumhoz, mindössze néhány sorral. kódsorok.

{{% blocks/products/pf/agp/code-block title="Python kód a PDF szerkesztéséhez" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PDF szerkesztése Pythonban" >}}


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
Töltse be a szerkeszteni kívánt PDF dokumentumot.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy új szövegsort.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a módosított PDF fájlt.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Más fájlok szerkesztése" subTitle="Más formátumú fájlokat is szerkeszthet" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}