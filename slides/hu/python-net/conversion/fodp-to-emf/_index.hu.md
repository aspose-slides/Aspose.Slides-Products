---
title: Konvertálja a FODP-t EMF-vé Pythonban
weight: 20
url: /hu/python-net/conversion/fodp-to-emf/ 
keywords: "Convert, PowerPoint, FODP, EMF, Presentation, Python"
description: Mintakód a FODP-ből EMF-be Python konvertáláshoz. Használja a PowerPoint Python API-t a FODP-fájlok EMF-fájlokká konvertálásához.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertálja a FODP-t EMF-vé Pythonban" h2="Hatékony PowerPoint Python könyvtár az FODP EMF-vé való konvertálásához" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konvertálja a FODP-t EMF-vé Pythonban" %}}

A FODP fájlokat programozottan EMF-re kell konvertálni? Az [*Aspose.Slides for Python .NET-en keresztüli használatával*](https://products.aspose.com/slides/hu/python-net/) bármely fejlesztő konvertálhatja a FODP-t EMF formátumba, mindössze néhány sor Python kóddal.

Modern prezentáció-feldolgozási API-ként az Aspose.Slides for Python gyorsan létrehozza az EMF-et FODP-ből. Tesztelje a FODP EMF konvertálás minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi a FODP fájlok számos népszerű formátumba való konvertálását.

A könyvtárat a [PyPI]-ről (https://pypi.org/project/Aspose.Slides/) telepítheti a következő pip paranccsal:

{{% blocks/products/pf/agp/code-block title="Konzol/Terminál" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Hogyan lehet FODP-t EMF-vé konvertálni a Pythonban" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések egy FODP-fájl EMF-re konvertálásához Python használatával." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltsön be FODP-fájlt a Presentation osztály egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.EMF-et
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az FODP fájl a megadott elérési úton kerül mentésre
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

{{% blocks/products/pf/agp/code-block title="Ez a mintakód a FODP-t EMF-be Python konverziót mutatja" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Mentse el a FODP-t EMF-ként a Pythonban" %}}
Használja az ingyenes alkalmazást a FODP EMF konvertálási folyamat bemutatójának megtekintéséhez. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="fodp-to-emf"
        sectionTitle="Ingyenes alkalmazás a FODP konvertálásához EMF -re" 
        sectionDescription="[Próbálja ki az ingyenes Collage alkalmazást](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A FODP-t sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument prezentációs formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="Hordozható hálózati grafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Makró-képes diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-svg/" name="FODP TO SVG" description="Skálázható vektorgrafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML papírspecifikációk" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}