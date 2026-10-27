---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertálja a PNG-t PPTX-re Pythonban
url: /hu/python-net/conversion/png-to-pptx/
keywords: PNG konvertálása PPTX-re, PNG-ből PPTX-re, PowerPoint, PNG, PPTX, Python API, Python Library
description: Konvertálja a PNG-t PPTX-re Pythonban. Használja a Python könyvtár API-t a PNG-képek PowerPoint formátumba konvertálásához
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertálja a PNG-t PPTX-re Pythonban" h2="Hatékony, többplatformos Python API PNG-ből PPTX-vé konvertálásához Python kóddal" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a PNG-t PPTX-re Pythonban" variant="code" %}}

Az [**Aspose.Slides for Python .NET-en keresztül**](https://products.aspose.com/slides/hu/python-net/) használatával néhány sornyi kóddal PNG-képet PowerPoint-prezentációvá konvertálhat:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python kód a PNG PPTX-vé konvertálásához" >}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PNG konvertálása PPTX-re az Aspose.Slides segítségével" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár, amellyel PowerPoint-prezentációkat, PDF-eket, HTML dokumentumokat és egyéb fájlokat. Amikor PNG-t PPTX-re konvertál, lényegében egy PowerPoint-prezentációt hoz létre, amely PNG-képek alapján tartalmaz diákat.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan lehet PNG-t PPTX-re konvertálni a Pythonban" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az **Aspose.Slides for Python programot .NET-en keresztül**. Lásd: [**Telepítés**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a könyvtárat referenciaként a projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy példányt a Prezentáció osztályból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX-re konvertálni kívánt PNG-képet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse el a kapott fájlt PPTX-prezentációként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Az Aspose.Slides segítségével készült" title="PNG konvertálása PPTX formátumba online" description="Az ingyenes Aspose.Slides Conversion alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PNG fájljaival." button="Aspose.Slides Conversion megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" upload="Húzza ide vagy töltse fel a fájlt" saveAs="Mentés másként" convert="Konvertálás" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan konvertálja a fájlokat az Aspose.Slides, mielőtt kódot írna.
- Töltsön fel PNG fájlokat, és mentse őket PPTX formátumban.
- Töltse le az eredményt, vagy konvertáljon további fájlokat.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott PowerPoint-konverziók" subTitle="Más formátumú fájlokat is konvertálhat PowerPointba" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
