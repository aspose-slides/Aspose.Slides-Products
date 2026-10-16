---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A(z) POTX konvertálása OTP formátumra JavaScriptben
url: /hu/nodejs-net/conversion/potx-to-otp/
keywords: POTX to OTP, POTX konvertálása OTP formátumba, Node.js API, JavaScript Library, POTX, OTP
description: A(z) POTX konvertálása OTP formátumra JavaScriptben. Használja a Node.js könyvtár API-t a POTX fájlok konvertálásához OTP formátumba
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A(z) POTX konvertálása OTP formátumra JavaScriptben" h2="Az Aspose.Slides for Node.js a .NET-en keresztül egy hatékony és könnyen használható könyvtár, amely lehetővé teszi PowerPoint-prezentációk konvertálását különböző formátumokba JavaScriptben. Támogatja az összes prezentációs elemet és formátumot, és gazdag API-t biztosít ezek eléréséhez és módosításához. Azt is lehetővé teszi, hogy diákjait különféle formátumokba exportálja további feldolgozás vagy megosztás céljából." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A POTX konvertálása OTP formátumra JavaScript használatával" variant="code" %}}

A POTX formátum OTP formátumra konvertálásához létre kell hoznia egy prezentációt a POTX fájlból, és el kell mentenie OTP néven.

{{< blocks/products/pf/slides-design-update-10-2026/code title="JavaScript kód a POTX OTP formátumba való konvertálásához" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potx");
try
{
    pres.save("output.otp", SaveFormat.Otp);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A(z) POTX konvertálása OTP formátumra a Node.js-ben" %}}

[**Aspose.Slides for Node.js .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/) egy hatékony Node.js könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a POTX OTP formátumra való konvertálására. Az **Aspose.Slides for Node.js .NET-en keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a POTX fájlokat OTP fájlokra, mindössze néhány sornyi kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Node.js .NET-en keresztül gyorsan exportál POTX fájlokat OTP fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) POTX fájl konvertálását OTP-re és sok más fájlformátumra

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="A(z) POTX konvertálása OTP formátumba az Aspose.Slides for Node.js használatával .NET API-n keresztül" intro="A(z) POTX formátumra OTP konvertálásához az Aspose.Slides for Node.js használatával .NET-en keresztül, importálnia kell a csomagot a JavaScript-fájlba, és létre kell hoznia a Presentation osztály példányát. A Presentation osztály egy PowerPoint-dokumentumot képvisel, és módszereket biztosít az elemek eléréséhez és kezeléséhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az [**Aspose.Slides for Node.js programot .NET-en keresztül**](https://products.aspose.com/slides/hu/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Node.js projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a POTX forrásfájlokat a Node.js-ben.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az eredmény mentése OTP fájlként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="A(z) POTX konvertálása más támogatott formátumokká" subTitle="A POTX formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/nodejs-net/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
