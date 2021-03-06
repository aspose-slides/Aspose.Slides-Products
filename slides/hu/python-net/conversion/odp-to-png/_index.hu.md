---
title: Konvertálja az ODP-t PNG-re Pythonban
weight: 310
url: /hu/python-net/conversion/odp-to-png/ 
keywords: "Convert, PowerPoint, ODP, PNG, Presentation, Python"
description: Mintakód az ODP-ből PNG-be való Python konvertáláshoz. Használja a PowerPoint Python API-t az ODP-fájlok PNG-fájlokká konvertálásához.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertálja az ODP-t PNG-re Pythonban" h2="Hatékony PowerPoint Python könyvtár az ODP PNG-re konvertálásához" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konvertálja az ODP-t PNG-re Pythonban" %}}

Programozottan kell konvertálnia az ODP fájlokat PNG formátumba? Az [*Aspose.Slides for Python .NET-en keresztül*] használatával (https://products.aspose.com/slides/hu/python-net/) bármely fejlesztő néhány sor Python kóddal PNG formátumba konvertálhatja az ODP-t.

Modern prezentációfeldolgozási API-ként az Aspose.Slides for Python gyorsan hoz létre PNG-t az ODP-ből. Tesztelje az ODP-PNG konverzió minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion/ppt-to-png). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi az ODP-fájlok számos népszerű formátumba való konvertálását.

A könyvtárat a [PyPI]-ről (https://pypi.org/project/Aspose.Slides/) telepítheti a következő pip paranccsal:

{{% blocks/products/pf/agp/code-block title="Konzol/Terminál" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Hogyan lehet az ODP-t PNG-re konvertálni a Pythonban" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések egy ODP-fájl PNG-re konvertálásához Python használatával." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be az ODP-fájlt a Prezentáció osztály példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.PNG-t
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az ODP fájl a megadott elérési útra kerül mentésre
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Python konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy Linux alapú operációs rendszer (lásd [tovább](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 vagy újabb
- A projektben hivatkozott Aspose.Slides for Python.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a mintakód az ODP-ből PNG-be való Python konvertálást mutatja be" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Mentse el az ODP-t PNG-ként a Pythonban" %}}
Használja az ingyenes alkalmazást az ODP-PNG átalakítási folyamat bemutatójának megtekintéséhez. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="odp-to-png"
        sectionTitle="Ingyenes alkalmazás a ODP konvertálásához PNG -re" 
        sectionDescription="[Próbálja ki az ingyenes alkalmazást a PPT konvertálásához PNG -re](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Az ODP-t sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-emf/" name="ODP TO EMF" description="Továbbfejlesztett metafájl formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-fodp/" name="ODP TO FODP" description="OpenDocument Flat XML-bemutató" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-jpg/" name="ODP TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-pdf/" name="ODP TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Makró-képes diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-svg/" name="ODP TO SVG" description="Skálázható vektorgrafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-swf/" name="ODP TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/odp-to-xps/" name="ODP TO XPS" description="XML papírspecifikációk" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}