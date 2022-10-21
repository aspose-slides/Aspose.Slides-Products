---
title: Egyesítse a FODP fájlokat a BMP formátumba Python használatával
url: /hu/python-net/merge/fodp-to-bmp/
keywords: A(z) FODP egyesítése a(z) BMP formátumba, a(z) FODP csatlakozása a(z) BMP formátumba, a(z)(FODP) összevonása a(z) BMP formátumba, PowerPoint, Presentation, BMP, Python, Aspose
description: Egyesítsen több FODP fájlt a Pythonban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Egyesítse a FODP fájlokat a BMP formátumba a Pythonban" h2="Nagy sebességű és többplatformos Python API, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Egyesítse a FODP formátumot a BMP formátumba a Pythonban" %}}

Az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít több FODP prezentáció kombinálására. Ha egy prezentációt egyesít egy másikkal, akkor hatékonyan egyesíti a diáikat egyetlen prezentációban, így egyetlen fájlt kap. Az Aspose.Slides lehetővé teszi, hogy két prezentációt különböző módon egyesítsen. Egyesítheti a prezentációkat minden formájával, stílusával, szövegével, formázásával, megjegyzéseivel, animációival stb. anélkül, hogy aggódnia kellene a minőség- vagy adatvesztés miatt.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyesítse a FODP fájlokat a BMP fájlba Python használatával" %}}
A PowerPoint-prezentációk egyesítéséhez klónoznia kell a diákat egyik prezentációból a másikba.

{{% blocks/products/pf/agp/code-block title="Python-kód több FODP egyesítéséhez egyetlen BMP fájlba" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.fodp") as pres1:
    with slides.Presentation("presentation2.fodp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A FODP és a BMP egyesítése az Aspose.Slides for Python API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések két FODP fájl egyesítéséhez és az eredmény mentéséhez BMP formátumban a Pythonban." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Python-projekthez.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a FODP forrásfájlokat a Pythonban.
```
pres1 = slides.Presentation('pres1.fodp')
pres2 = slides.Presentation('pres2.fodp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinálja a FODP fájlokat az [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) módszerrel.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse a prezentációt, és kapja meg az eredményt egyetlen BMP fájlként.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="FODP exportálása más támogatott formátumokba" subTitle="A FODP formátumot kombinálhatja is, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-pptx/" name="FODP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-ppt/" name="FODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-pdf/" name="FODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-html/" name="FODP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-png/" name="FODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-jpg/" name="FODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-gif/" name="FODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-odp/" name="FODP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-otp/" name="FODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-pot/" name="FODP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-potm/" name="FODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-potx/" name="FODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-pps/" name="FODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-ppsm/" name="FODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-ppsx/" name="FODP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-pptm/" name="FODP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-svg/" name="FODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-tiff/" name="FODP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp-to-xps/" name="FODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}