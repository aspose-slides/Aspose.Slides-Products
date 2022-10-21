---
title: Egyesítse a OTP fájlokat a TIFF formátumba Python használatával
url: /hu/python-net/merge/otp-to-tiff/
keywords: A(z) OTP egyesítése a(z) TIFF formátumba, a(z) OTP csatlakozása a(z) TIFF formátumba, a(z)(OTP) összevonása a(z) TIFF formátumba, PowerPoint, Presentation, TIFF, Python, Aspose
description: Egyesítsen több OTP fájlt a Pythonban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Egyesítse a OTP fájlokat a TIFF formátumba a Pythonban" h2="Nagy sebességű és többplatformos Python API, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Egyesítse a OTP formátumot a TIFF formátumba a Pythonban" %}}

Az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít több OTP prezentáció kombinálására. Ha egy prezentációt egyesít egy másikkal, akkor hatékonyan egyesíti a diáikat egyetlen prezentációban, így egyetlen fájlt kap. Az Aspose.Slides lehetővé teszi, hogy két prezentációt különböző módon egyesítsen. Egyesítheti a prezentációkat minden formájával, stílusával, szövegével, formázásával, megjegyzéseivel, animációival stb. anélkül, hogy aggódnia kellene a minőség- vagy adatvesztés miatt.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyesítse a OTP fájlokat a TIFF fájlba Python használatával" %}}
A PowerPoint-prezentációk egyesítéséhez klónoznia kell a diákat egyik prezentációból a másikba.

{{% blocks/products/pf/agp/code-block title="Python-kód több OTP egyesítéséhez egyetlen TIFF fájlba" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.otp") as pres1:
    with slides.Presentation("presentation2.otp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A OTP és a TIFF egyesítése az Aspose.Slides for Python API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések két OTP fájl egyesítéséhez és az eredmény mentéséhez TIFF formátumban a Pythonban." >}}

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
Nyissa meg a OTP forrásfájlokat a Pythonban.
```
pres1 = slides.Presentation('pres1.otp')
pres2 = slides.Presentation('pres2.otp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinálja a OTP fájlokat az [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) módszerrel.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse a prezentációt, és kapja meg az eredményt egyetlen TIFF fájlként.
```
pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="OTP exportálása más támogatott formátumokba" subTitle="A OTP formátumot kombinálhatja is, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-pptx/" name="OTP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-ppt/" name="OTP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-pdf/" name="OTP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-html/" name="OTP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-png/" name="OTP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-bmp/" name="OTP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-jpg/" name="OTP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-fodp/" name="OTP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-gif/" name="OTP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-odp/" name="OTP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-pot/" name="OTP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-potm/" name="OTP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-potx/" name="OTP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-pps/" name="OTP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-ppsm/" name="OTP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-ppsx/" name="OTP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-pptm/" name="OTP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-svg/" name="OTP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp-to-xps/" name="OTP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}