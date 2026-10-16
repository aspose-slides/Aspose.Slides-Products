---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A(z) FODP konvertálása SVG formátumra JavaScriptben
url: /hu/nodejs-net/conversion/fodp-to-svg/
keywords: FODP to SVG, FODP konvertálása SVG formátumba, Node.js API, JavaScript Library, FODP, SVG
description: A(z) FODP konvertálása SVG formátumra JavaScriptben. Használja a Node.js könyvtár API-t a FODP fájlok konvertálásához SVG formátumba
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A(z) FODP konvertálása SVG formátumra JavaScriptben" h2="Az Aspose.Slides for Node.js a .NET-en keresztül egy hatékony és könnyen használható könyvtár, amely lehetővé teszi PowerPoint-prezentációk konvertálását különböző formátumokba JavaScriptben. Támogatja az összes prezentációs elemet és formátumot, és gazdag API-t biztosít ezek eléréséhez és módosításához. Azt is lehetővé teszi, hogy diákjait különféle formátumokba exportálja további feldolgozás vagy megosztás céljából." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A FODP konvertálása SVG formátumra JavaScript használatával" variant="code" %}}

A FODP formátum SVG formátumra konvertálásához létre kell hoznia egy prezentációt a FODP fájlból, és el kell mentenie SVG néven.

{{< blocks/products/pf/slides-design-update-10-2026/code title="JavaScript kód a FODP SVG formátumba való konvertálásához" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.fodp");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A(z) FODP konvertálása SVG formátumra a Node.js-ben" %}}

[**Aspose.Slides for Node.js .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/) egy hatékony Node.js könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a FODP SVG formátumra való konvertálására. Az **Aspose.Slides for Node.js .NET-en keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a FODP fájlokat SVG fájlokra, mindössze néhány sornyi kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Node.js .NET-en keresztül gyorsan exportál FODP fájlokat SVG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) FODP fájl konvertálását SVG-re és sok más fájlformátumra

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="A(z) FODP konvertálása SVG formátumba az Aspose.Slides for Node.js használatával .NET API-n keresztül" intro="A(z) FODP formátumra SVG konvertálásához az Aspose.Slides for Node.js használatával .NET-en keresztül, importálnia kell a csomagot a JavaScript-fájlba, és létre kell hoznia a Presentation osztály példányát. A Presentation osztály egy PowerPoint-dokumentumot képvisel, és módszereket biztosít az elemek eléréséhez és kezeléséhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az [**Aspose.Slides for Node.js programot .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Node.js projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a FODP forrásfájlokat a Node.js-ben.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az eredmény mentése SVG fájlként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="A(z) FODP konvertálása más támogatott formátumokká" subTitle="A FODP formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
