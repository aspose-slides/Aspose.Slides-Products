---
title: Egyesítse a PPT fájlokat a PNG formátumba Python használatával
url: /hu/python-net/merge/ppt-to-png/
keywords: A(z) PPT egyesítése a(z) PNG formátumba, a(z) PPT csatlakozása a(z) PNG formátumba, a(z)(PPT) összevonása a(z) PNG formátumba, PowerPoint, Presentation, PNG, Python, Aspose
description: Egyesítsen több PPT fájlt a Pythonban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Egyesítse a PPT fájlokat a PNG formátumba a Pythonban" h2="Nagy sebességű és többplatformos Python API, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Egyesítse a PPT formátumot a PNG formátumba a Pythonban" %}}

Az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít több PPT prezentáció kombinálására. Ha egy prezentációt egyesít egy másikkal, akkor hatékonyan egyesíti a diáikat egyetlen prezentációban, így egyetlen fájlt kap. Az Aspose.Slides lehetővé teszi, hogy két prezentációt különböző módon egyesítsen. Egyesítheti a prezentációkat minden formájával, stílusával, szövegével, formázásával, megjegyzéseivel, animációival stb. anélkül, hogy aggódnia kellene a minőség- vagy adatvesztés miatt.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyesítse a PPT fájlokat a PNG fájlba Python használatával" %}}
A PowerPoint-prezentációk egyesítéséhez klónoznia kell a diákat egyik prezentációból a másikba.

{{% blocks/products/pf/agp/code-block title="Python-kód több PPT egyesítéséhez egyetlen PNG fájlba" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.ppt") as pres1:
    with slides.Presentation("presentation2.ppt") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PPT és a PNG egyesítése az Aspose.Slides for Python API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések két PPT fájl egyesítéséhez és az eredmény mentéséhez PNG formátumban a Pythonban." >}}

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
Nyissa meg a PPT forrásfájlokat a Pythonban.
```
pres1 = slides.Presentation('pres1.ppt')
pres2 = slides.Presentation('pres2.ppt')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinálja a PPT fájlokat az [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) módszerrel.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse a prezentációt, és kapja meg az eredményt egyetlen PNG fájlként.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPT exportálása más támogatott formátumokba" subTitle="A PPT formátumot kombinálhatja is, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-pptx/" name="PPT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-pdf/" name="PPT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-html/" name="PPT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-bmp/" name="PPT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-jpg/" name="PPT TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-fodp/" name="PPT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-gif/" name="PPT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-odp/" name="PPT TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-otp/" name="PPT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-pot/" name="PPT TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-potm/" name="PPT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-potx/" name="PPT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-pps/" name="PPT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-ppsm/" name="PPT TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-ppsx/" name="PPT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-pptm/" name="PPT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-svg/" name="PPT TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-tiff/" name="PPT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt-to-xps/" name="PPT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}