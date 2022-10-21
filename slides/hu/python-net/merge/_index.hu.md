---
title: Egyesítsen PDF, PPT, PPTX és sok más fájlformátumot Python segítségével
url: /hu/python-net/merge/
keywords: Egyesítés, csatlakozás, PowerPoint, prezentáció, Python, Aspose
description: Egyesítsen több fájlt Python PPT, PPTX, ODP, PDF, PNG, JPG és még sok más formátumban.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Egyesítse a Powerpointot, PDF-et, PPT-t vagy más dokumentumokat Pythonban" h2="Nagy sebességű Python könyvtár a PPT, PPTX, PDF, PNG, JPEG és más formátumok egyesítéséhez." >}}

{{% blocks/products/pf/feature-page-section h2="PPT, PPTX, PDF egyesítése Python segítségével" %}}

Az [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hu/python-net/) egy hatékony Python-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít több PPT/PPTX prezentáció kombinálására. Ha egy prezentációt egyesít egy másikkal, akkor hatékonyan egyesíti a diáikat egyetlen prezentációban, így egyetlen fájlt kap. Az Aspose.Slides lehetővé teszi, hogy két prezentációt különböző módon egyesítsen. Egyesítheti a prezentációkat minden formájával, stílusával, szövegével, formázásával, megjegyzéseivel, animációival stb. anélkül, hogy aggódnia kellene a minőség- vagy adatvesztés miatt.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint prezentációk egyesítése Pythonban" %}}
A PowerPoint-prezentációk egyesítéséhez klónoznia kell a diákat egyik prezentációból a másikba.

{{% blocks/products/pf/agp/code-block title="Egyesítse a PPTX fájlokat Python segítségével" offSpacer="true" %}}

```python

import aspose.slides as slides

# open first presentation
with slides.Presentation("presentation1.pptx") as pres1:
    # open second presentation
    with slides.Presentation("presentation2.pptx") as pres2:
        # loop through slides
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
        # save merged presentation
        pres1.save("combined.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Egyesítse a prezentációkat a Slide Master programmal Python használatával" %}}
Ez a python-kód bemutatja, hogyan egyesíthet több prezentációt egybe, és hogyan alkalmazhat stílusokat a diamester-prezentációs sablonból. Így az eredményprezentáció ugyanazt a forrásformázást fogja megtartani, és egy másik prezentáció mesterdiájából származó formázást is tartalmazni fogja.

{{% blocks/products/pf/agp/code-block title="Egyesítsen több PPT-t egyetlenvé a Pythonban" offSpacer="true" %}}

```python

import aspose.slides as slides

files = ['pres1.pptx', 'pres2.pptx', 'pres3.pptx']

with slides.Presentation('master.pptx') as master:
    masterSlide = master.masters[0]

    for file in files:
        with slides.Presentation(file) as source:
            for slide in source.slides:
                clone = master.slides.add_clone(slide)

                for shape in masterSlide.shapes:
                    clone.shapes.add_clone(shape)
    
    master.save("combined.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Prezentációk egyesítése az Aspose.Slides for Python API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések két PPTX fájl egyesítéséhez és az eredmény PDF formátumban történő mentéséhez a Pythonban." >}}

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
Nyissa meg a forrás PPTX fájlokat a Pythonban.
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinálja a PPTX fájlokat az **add_clone** módszerrel.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse a bemutatót, és kapja meg az eredményt egyetlen PDF-fájlként.
```
pres1.save("document.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott formátumok egyesítése" subTitle="Más fájlformátumokat is kombinálhat. Lásd alább a többi támogatott formátumot." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppt/" name="PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/pptx/" name="PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/pdf/" name="PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/odp/" name="ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/otp/" name="OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/pot/" name="POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/potm/" name="POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/potx/" name="POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/pps/" name="PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsm/" name="PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/ppsx/" name="PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/pptm/" name="PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/merge/fodp/" name="FODP" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}