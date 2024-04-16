---
title: Konvertálja a(z) PPSX fájlt PNG formátumra a Pythonban
url: /hu/python-java/conversion/ppsx-to-png/
keywords: Python prezentáció konvertálás, prezentációk konvertálása Python formátumba, Python prezentációkhoz, Aspose.Slides Python, PPSX konvertálása PNG formátumba, Python prezentációs könyvtár
description: Konvertálja a(z) PPSX fájlt PNG formátumra a Pythonban. Használja a Python könyvtár API-t a PPSX fájlok konvertálásához PNG formátumba
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Könnyedén konvertálja a PPSX formátumot PNG formátumba a Python segítségével: Aspose.Slides to the Rescue!" h2="Lélegezzen új életet prezentációiba a Python segítségével. Útmutatónk végigvezeti Önt a meglévő PowerPoint-diák vonzó Python-prezentációkká alakításán." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a(z) PPSX fájlt PNG formátumra a Pythonban" %}}

Belefáradt a bonyolult prezentációs szoftverekkel való birkózásba? Ne keressen tovább, mint [**Aspose.Slides for Python Java-n keresztül**](https://products.aspose.com/slides/hu/python-java/)! Ez a hatékony könyvtár lehetővé teszi a prezentációk egyszerű létrehozását, szerkesztését és konvertálását a különböző formátumok között. Váltson PPSX-ról PNG-re? Az Aspose.Slides gyerekjáték, mindössze néhány sor Python kódot igényel.

A legmodernebb dokumentumfeldolgozó API-ként az **Aspose.Slides for Python via Java** villámgyors konverziós sebességgel büszkélkedhet, amely biztosítja a PPSX prezentációk gyors átalakítását PNG formátumba. Kerülje el a hagyományos eszközök korlátait – Az Aspose.Slides rugalmasságot biztosít a prezentációk PPSX-ról nem csak PNG-re konvertálására, hanem számos más formátumra is, így lehetővé teszi, hogy prezentációit bármilyen helyzethez hibátlanul igazítsa.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a(z) PPSX formátumot PNG formátumra Python használatával" %}}
A PPSX formátum PNG formátumra konvertálásához létre kell hoznia egy prezentációt a PPSX fájlból, és el kell mentenie PNG néven.

{{% blocks/products/pf/agp/code-block title="Python oktatóanyag a PPSX PNG formátumba való konvertálásához" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppsx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python oktatóanyag. A(z) PPSX konvertálása PNG formátumba az Aspose.Slides for Python használatával Java API-n keresztül." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="A {from_formátum} PNG formátumra való konvertálásához az Aspose.Slides for Python segítségével Java segítségével, importálnia kell a csomagot a Python-szkriptbe, és létre kell hoznia egy példányt a Presentation osztályból. A Presentation osztály egy PowerPoint-dokumentumot képvisel, és módszereket biztosít az elemek eléréséhez és kezeléséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for Python programot Java-n keresztül**](https://products.aspose.com/slides/hu/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Python-projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a PPSX forrásfájlokat a Pythonban.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PNG fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) PPSX konvertálása más támogatott formátumokká" subTitle="A PPSX formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}