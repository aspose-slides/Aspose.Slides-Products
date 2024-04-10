---
title: A(z) POT konvertálása PNG formátumra JavaScriptben
url: /hu/nodejs-net/conversion/pot-to-png/
keywords: POT to PNG, POT konvertálása PNG formátumba, Node.js API, JavaScript Library, POT, PNG
description: A(z) POT konvertálása PNG formátumra JavaScriptben. Használja a Node.js könyvtár API-t a POT fájlok konvertálásához PNG formátumba
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="A(z) POT konvertálása PNG formátumra JavaScriptben" h2="Az Aspose.Slides for Node.js a .NET-en keresztül egy hatékony és könnyen használható könyvtár, amely lehetővé teszi PowerPoint-prezentációk konvertálását különböző formátumokba JavaScriptben. Támogatja az összes prezentációs elemet és formátumot, és gazdag API-t biztosít ezek eléréséhez és módosításához. Azt is lehetővé teszi, hogy diákjait különféle formátumokba exportálja további feldolgozás vagy megosztás céljából." >}}

{{% blocks/products/pf/feature-page-section h2="A(z) POT konvertálása PNG formátumra a Node.js-ben" %}}

[**Aspose.Slides for Node.js .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/) egy hatékony Node.js könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a POT PNG formátumra való konvertálására. Az **Aspose.Slides for Node.js .NET-en keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a POT fájlokat PNG fájlokra, mindössze néhány sornyi kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Node.js .NET-en keresztül gyorsan exportál POT fájlokat PNG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) POT fájl konvertálását PNG-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A POT konvertálása PNG formátumra JavaScript használatával" %}}
A POT formátum PNG formátumra konvertálásához létre kell hoznia egy prezentációt a POT fájlból, és el kell mentenie PNG néven.

{{% blocks/products/pf/agp/code-block title="JavaScript kód a POT PNG formátumba való konvertálásához" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pot");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".png", ImageFormat.Png); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A(z) POT konvertálása PNG formátumba az Aspose.Slides for Node.js használatával .NET API-n keresztül" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="A(z) POT formátumra PNG konvertálásához az Aspose.Slides for Node.js használatával .NET-en keresztül, importálnia kell a csomagot a JavaScript-fájlba, és létre kell hoznia a Presentation osztály példányát. A Presentation osztály egy PowerPoint-dokumentumot képvisel, és módszereket biztosít az elemek eléréséhez és kezeléséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for Node.js programot .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Node.js projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a POT forrásfájlokat a Node.js-ben.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PNG fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) POT konvertálása más támogatott formátumokká" subTitle="A POT formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/nodejs-net/conversion/pot-to-tiff/" name="POT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}