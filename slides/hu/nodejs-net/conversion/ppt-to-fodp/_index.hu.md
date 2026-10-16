---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A(z) PPT konvertálása FODP formátumra JavaScriptben
url: /hu/nodejs-net/conversion/ppt-to-fodp/
keywords: PPT to FODP, PPT konvertálása FODP formátumba, Node.js API, JavaScript Library, PPT, FODP
description: A(z) PPT konvertálása FODP formátumra JavaScriptben. Használja a Node.js könyvtár API-t a PPT fájlok konvertálásához FODP formátumba
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A(z) PPT konvertálása FODP formátumra JavaScriptben" h2="Az Aspose.Slides for Node.js a .NET-en keresztül egy hatékony és könnyen használható könyvtár, amely lehetővé teszi PowerPoint-prezentációk konvertálását különböző formátumokba JavaScriptben. Támogatja az összes prezentációs elemet és formátumot, és gazdag API-t biztosít ezek eléréséhez és módosításához. Azt is lehetővé teszi, hogy diákjait különféle formátumokba exportálja további feldolgozás vagy megosztás céljából." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A PPT konvertálása FODP formátumra JavaScript használatával" variant="code" %}}

A PPT formátum FODP formátumra konvertálásához létre kell hoznia egy prezentációt a PPT fájlból, és el kell mentenie FODP néven.

{{< blocks/products/pf/slides-design-update-10-2026/code title="JavaScript kód a PPT FODP formátumba való konvertálásához" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppt");
try
{
    pres.save("output.fodp", SaveFormat.Fodp);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A(z) PPT konvertálása FODP formátumra a Node.js-ben" %}}

[**Aspose.Slides for Node.js .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/) egy hatékony Node.js könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a PPT FODP formátumra való konvertálására. Az **Aspose.Slides for Node.js .NET-en keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a PPT fájlokat FODP fájlokra, mindössze néhány sornyi kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Node.js .NET-en keresztül gyorsan exportál PPT fájlokat FODP fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) PPT fájl konvertálását FODP-re és sok más fájlformátumra

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="A(z) PPT konvertálása FODP formátumba az Aspose.Slides for Node.js használatával .NET API-n keresztül" intro="A(z) PPT formátumra FODP konvertálásához az Aspose.Slides for Node.js használatával .NET-en keresztül, importálnia kell a csomagot a JavaScript-fájlba, és létre kell hoznia a Presentation osztály példányát. A Presentation osztály egy PowerPoint-dokumentumot képvisel, és módszereket biztosít az elemek eléréséhez és kezeléséhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az [**Aspose.Slides for Node.js programot .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Node.js projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a PPT forrásfájlokat a Node.js-ben.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az eredmény mentése FODP fájlként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="A(z) PPT konvertálása más támogatott formátumokká" subTitle="A PPT formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
