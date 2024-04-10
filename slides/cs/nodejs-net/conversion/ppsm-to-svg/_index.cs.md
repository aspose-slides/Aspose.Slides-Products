---
title: Převeďte PPSM do SVG v JavaScriptu
url: /cs/nodejs-net/conversion/ppsm-to-svg/
keywords: PPSM do SVG, Převést PPSM do SVG, Node.js API, JavaScript Library, PPSM, SVG
description: Převeďte PPSM do SVG v JavaScriptu. Pomocí rozhraní API knihovny Node.js převeďte soubory PPSM na SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte PPSM do SVG v JavaScriptu" h2="Aspose.Slides for Node.js přes .NET je výkonná a snadno použitelná knihovna, která vám umožňuje převádět PowerPointové prezentace do různých formátů v JavaScriptu. Podporuje všechny prezentační prvky a formáty a poskytuje bohaté API pro přístup a úpravu. Umožňuje také exportovat snímky do různých formátů pro další zpracování nebo sdílení." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PPSM na SVG v Node.js" %}}

[**Aspose.Slides pro Node.js přes .NET**](https://products.aspose.com/slides/cs/nodejs-net/) je výkonná knihovna Node.js pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu PPSM do SVG. Pomocí **Aspose.Slides for Node.js přes .NET** může každý vývojář nebo aplikace převést soubory PPSM do SVG pomocí několika řádků kódu.

Aspose.Slides pro Node.js přes .NET jako moderní API pro zpracování dokumentů rychle exportuje soubory PPSM do formátů souborů SVG. Knihovna Aspose PowerPoint vám umožňuje převést PPSM do SVGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte PPSM do SVG pomocí JavaScriptu" %}}
Chcete-li převést PPSM do SVG, budete muset vytvořit prezentaci ze souboru PPSM a uložit ji jako SVG.

{{% blocks/products/pf/agp/code-block title="JavaScript kód pro převod PPSM do SVG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppsm");
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést PPSM do SVG pomocí Aspose.Slides pro Node.js přes .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Chcete-li převést PPSM na SVG pomocí Aspose.Slides for Node.js přes .NET, musíte importovat balíček do souboru JavaScript a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides pro Node.js přes .NET**](https://products.aspose.com/slides/cs/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory PPSM v Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést PPSM do jiných podporovaných formátů" subTitle="Můžete také převést PPSM a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}