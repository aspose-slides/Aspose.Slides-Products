---
title: Převeďte OTP do BMP v JavaScriptu
url: /cs/nodejs-net/conversion/otp-to-bmp/
keywords: OTP do BMP, Převést OTP do BMP, Node.js API, JavaScript Library, OTP, BMP
description: Převeďte OTP do BMP v JavaScriptu. Pomocí rozhraní API knihovny Node.js převeďte soubory OTP na BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte OTP do BMP v JavaScriptu" h2="Aspose.Slides for Node.js přes .NET je výkonná a snadno použitelná knihovna, která vám umožňuje převádět PowerPointové prezentace do různých formátů v JavaScriptu. Podporuje všechny prezentační prvky a formáty a poskytuje bohaté API pro přístup a úpravu. Umožňuje také exportovat snímky do různých formátů pro další zpracování nebo sdílení." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte OTP na BMP v Node.js" %}}

[**Aspose.Slides pro Node.js přes .NET**](https://products.aspose.com/slides/cs/nodejs-net/) je výkonná knihovna Node.js pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu OTP do BMP. Pomocí **Aspose.Slides for Node.js přes .NET** může každý vývojář nebo aplikace převést soubory OTP do BMP pomocí několika řádků kódu.

Aspose.Slides pro Node.js přes .NET jako moderní API pro zpracování dokumentů rychle exportuje soubory OTP do formátů souborů BMP. Knihovna Aspose PowerPoint vám umožňuje převést OTP do BMPs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte OTP do BMP pomocí JavaScriptu" %}}
Chcete-li převést OTP do BMP, budete muset vytvořit prezentaci ze souboru OTP a uložit ji jako BMP.

{{% blocks/products/pf/agp/code-block title="JavaScript kód pro převod OTP do BMP" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.otp");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".bmp", ImageFormat.Bmp); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést OTP do BMP pomocí Aspose.Slides pro Node.js přes .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Chcete-li převést OTP na BMP pomocí Aspose.Slides for Node.js přes .NET, musíte importovat balíček do souboru JavaScript a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides pro Node.js přes .NET**](https://products.aspose.com/slides/cs/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory OTP v Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést OTP do jiných podporovaných formátů" subTitle="Můžete také převést OTP a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-net/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}