---
title: Egyesítse a PPSX fájlokat a PPTX formátumba Python használatával
url: /hu/python-net/merge/ppsx-to-pptx/
keywords: A(z) PPSX egyesítése a(z) PPTX formátumba, a(z) PPSX csatlakozása a(z) PPTX formátumba, a(z)(PPSX) összevonása a(z) PPTX formátumba, PowerPoint, Presentation, PPTX, Python, Aspose
description: Egyesítsen több PPSX fájlt a Pythonban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Egyesítse a PPSX fájlokat a PPTX formátumba a Pythonban" h2="Nagy sebességű és többplatformos Python API, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Egyesítse a PPSX formátumot a PPTX formátumba a Pythonban" %}}

Az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít több PPSX prezentáció kombinálására. Ha egy prezentációt egyesít egy másikkal, akkor hatékonyan egyesíti a diáikat egyetlen prezentációban, így egyetlen fájlt kap. Az Aspose.Slides lehetővé teszi, hogy két prezentációt különböző módon egyesítsen. Egyesítheti a prezentációkat minden formájával, stílusával, szövegével, formázásával, megjegyzéseivel, animációival stb. anélkül, hogy aggódnia kellene a minőség- vagy adatvesztés miatt.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyesítse a PPSX fájlokat a PPTX fájlba Python használatával" %}}
A PowerPoint-prezentációk egyesítéséhez klónoznia kell a diákat egyik prezentációból a másikba.

{{% blocks/products/pf/agp/code-block title="Python-kód több PPSX egyesítéséhez egyetlen PPTX fájlba" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.ppsx") as pres1:
    with slides.Presentation("presentation2.ppsx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PPSX és a PPTX egyesítése az Aspose.Slides for Python API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések két PPSX fájl egyesítéséhez és az eredmény mentéséhez PPTX formátumban a Pythonban." >}}

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
Nyissa meg a PPSX forrásfájlokat a Pythonban.
```
pres1 = slides.Presentation('pres1.ppsx')
pres2 = slides.Presentation('pres2.ppsx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinálja a PPSX fájlokat az [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) módszerrel.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse a prezentációt, és kapja meg az eredményt egyetlen PPTX fájlként.
```
pres1.save("presentation.pptx", slides.export.SaveFormat.PPTX)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPSX exportálása más támogatott formátumokba" subTitle="A PPSX formátumot kombinálhatja is, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-ppt/" name="PPSX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-pdf/" name="PPSX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-html/" name="PPSX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-png/" name="PPSX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-bmp/" name="PPSX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-jpg/" name="PPSX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-fodp/" name="PPSX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-gif/" name="PPSX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-odp/" name="PPSX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-otp/" name="PPSX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-pot/" name="PPSX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-potm/" name="PPSX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-potx/" name="PPSX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-pps/" name="PPSX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-pptm/" name="PPSX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-svg/" name="PPSX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-tiff/" name="PPSX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx-to-xps/" name="PPSX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}