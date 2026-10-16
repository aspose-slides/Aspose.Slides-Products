---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertálja a POT-ot PNG-re Pythonban
weight: 980
url: /hu/python-net/conversion/pot-to-png/ 
keywords: "Convert, PowerPoint, POT, PNG, Presentation, Python"
description: Mintakód a POT-ból PNG-be való Python konverzióhoz. Használja a PowerPoint Python API-t a POT-fájlok PNG-fájlokká konvertálásához.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertálja a POT-ot PNG-re Pythonban" h2="Hatékony PowerPoint Python-könyvtár a POT PNG-re konvertálásához"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a POT-ot PNG-re Pythonban" %}}

A POT fájlokat programozottan PNG formátumba kell konvertálni? Az [*Aspose.Slides for Python .NET-en keresztül történő használatával*](https://products.aspose.com/slides/hu/python-net/) bármely fejlesztő néhány sor Python kóddal POT-formátumba konvertálhatja.

Modern prezentációfeldolgozási API-ként az Aspose.Slides for Python gyorsan létrehozza a PNG-t a POT-ból. Tesztelje a POT–PNG konverzió minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion/ppt-to-png). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi a POT-fájlok számos népszerű formátumba való konvertálását.

A könyvtárat a [PyPI]-ről (https://pypi.org/project/Aspose.Slides/) telepítheti a következő pip paranccsal:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzol/Terminál" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POT mentése PNG-ként Pythonban" %}}

Használja az ingyenes alkalmazást a POT-ból PNG-be konvertálási folyamat bemutatójának megtekintéséhez.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ez a mintakód a POT-ból PNG-be való Python konvertálást mutatja" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pot") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan lehet a POT-ot PNG-re konvertálni a Pythonban" intro="Ezek a lépések a POT-fájl PNG-re konvertálásához Python használatával." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltsön be POT-fájlt a Prezentáció osztály példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.PNG-t{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A POT fájl a megadott elérési úton kerül mentésre{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="A Python konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." %}}

- Microsoft Windows vagy Linux alapú operációs rendszer (lásd [tovább](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 vagy újabb
- A projektben hivatkozott Aspose.Slides for Python.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes alkalmazás a POT konvertálásához PNG -re"
  description="[Próbálja ki az ingyenes alkalmazást a PPT konvertálásához PNG -re](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A POT-ot sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-bmp/" name="POT TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-emf/" name="POT TO EMF" description="Továbbfejlesztett metafájl formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-fodp/" name="POT TO FODP" description="OpenDocument Flat XML-bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-gif/" name="POT TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-html/" name="POT TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-jpg/" name="POT TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocument prezentációs formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-otp/" name="POT TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-pdf/" name="POT TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-potm/" name="POT TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-potx/" name="POT TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-pps/" name="POT TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Makró-képes diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-pptm/" name="POT TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-svg/" name="POT TO SVG" description="Skálázható vektorgrafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-swf/" name="POT TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/python-net/conversion/pot-to-xps/" name="POT TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
