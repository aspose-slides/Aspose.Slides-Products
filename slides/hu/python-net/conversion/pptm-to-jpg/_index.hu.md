---
title: Konvertálja a PPTM-et JPG-be Pythonban
weight: 2480
url: /hu/python-net/conversion/pptm-to-jpg/ 
keywords: "Convert, PowerPoint, PPTM, JPG, Presentation, Python"
description: Mintakód a PPTM-ből JPG-be Python konvertáláshoz. Használja a PowerPoint Python API-t a PPTM-fájlok JPG-fájlokká konvertálásához.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertálja a PPTM-et JPG-be Pythonban" h2="Hatékony PowerPoint Python könyvtár a PPTM JPG formátumba konvertálásához" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konvertálja a PPTM-et JPG-be Pythonban" %}}

Programozottan kell konvertálnia a PPTM fájlokat JPG formátumba? Az [*Aspose.Slides for Python for .NET használatával*](https://products.aspose.com/slides/hu/python-net/) bármely fejlesztő konvertálhatja a PPTM-et JPG formátumba, mindössze néhány sor Python kóddal.

Modern prezentációfeldolgozási API-ként az Aspose.Slides for Python gyorsan készít JPG-t PPTM-ből. Tesztelje a PPTM–JPG konvertálás minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion/ppt-to-jpg). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi a PPTM fájlok számos népszerű formátumba való konvertálását.

A könyvtárat a [PyPI]-ről (https://pypi.org/project/Aspose.Slides/) telepítheti a következő pip paranccsal:

{{% blocks/products/pf/agp/code-block title="Konzol/Terminál" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Hogyan lehet PPTM-et JPG-vé konvertálni Pythonban" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PPTM-fájlok JPG-formátumba konvertálásához Python használatával." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltsön be PPTM-fájlt a Presentation osztály egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.JPG-t
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPTM fájl a megadott elérési úton kerül mentésre
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

{{% blocks/products/pf/agp/code-block title="Ez a mintakód a PPTM-ből JPG-be való Python konvertálást mutat be" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="A PPTM mentése JPG formátumban Pythonban" %}}
Az ingyenes alkalmazás segítségével megtekintheti a PPTM-JPG konvertálási folyamat bemutatóját. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Ingyenes alkalmazás a PPTM konvertálásához JPG -re" 
        sectionDescription="[Próbálja ki az ingyenes alkalmazást a PPT konvertálásához JPG -re](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A PPTM-et számos más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="Továbbfejlesztett metafájl formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="OpenDocument Flat XML-bemutató" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument prezentációs formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-png/" name="PPTM TO PNG" description="Hordozható hálózati grafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Makró-képes diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Skálázható vektorgrafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="XML papírspecifikációk" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}