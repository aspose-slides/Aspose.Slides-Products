---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertálja a(z) SVG fájlt PNG formátumra a Pythonban
url: /hu/python-net/conversion/svg-to-png/
keywords: SVG to PNG, SVG konvertálása PNG formátumba, Python API, Python Library, SVG, PNG
description: Konvertálja a(z) SVG fájlt PNG formátumra a Pythonban. Használja a Python könyvtár API-t a SVG fájlok konvertálásához PNG formátumúvá
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertálja a(z) SVG fájlt PNG formátumra a Pythonban" h2="Nagy sebességű és többplatformos Python Library, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a(z) SVG fájlt PNG formátumra Python használatával" variant="code" %}}

A SVG formátum PNG formátumra konvertálásához létre kell hoznia egy prezentációt a SVG fájlból, és el kell mentenie PNG néven.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python kód a SVG PNG formátumba való konvertálásához" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a(z) SVG fájlt PNG formátumra a Pythonban" %}}

Az [**Aspose.Slides for Python .NET-en keresztül**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a SVG PNG formátumra való konvertálására. Az **Aspose.Slides for Python .NET-en keresztül** használatával bármely fejlesztő vagy alkalmazás képes a SVG fájlokat PNG fájlokra konvertálni, mindössze néhány sor Python kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Python gyorsan exportál SVG fájlokat PNG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) SVG fájl konvertálását PNG-re és sok más fájlformátumra

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="A SVG konvertálása PNG formátumba az Aspose.Slides for Python API használatával" intro="Ezek a lépések a SVG PNG formátumra való konvertálásához Pythonban." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Python-projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a SVG forrásfájlokat a Pythonban.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az eredmény mentése PNG fájlként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes online konverter"
  description="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="A(z) SVG konvertálása más támogatott formátumokká" subTitle="A SVG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
