---
title: Převeďte POT na BMP v Node.js
url: /cs/nodejs-java/conversion/pot-to-bmp/
keywords: POT do BMP, Převést POT do BMP, Node.js API, Node.js Library, POT, BMP
description: Převeďte POT na BMP v Node.js. K převodu souborů POT na BMP použijte rozhraní API knihovny Node.js
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte POT na BMP v Node.js" h2="Aspose.Slides for Node.js přes Javu je výkonná a snadno použitelná knihovna, která vám umožňuje převádět PowerPointové prezentace do různých formátů v Node.js. Podporuje všechny prezentační prvky a formáty a poskytuje bohaté API pro přístup a úpravu. Umožňuje také exportovat snímky do různých formátů pro další zpracování nebo sdílení." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte POT na BMP v Node.js" %}}

[**Aspose.Slides pro Node.js přes Javu**](https://products.aspose.com/slides/cs/nodejs-java/) je výkonná knihovna Node.js pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu POT do BMP. Pomocí **Aspose.Slides for Node.js přes Java** může každý vývojář nebo aplikace převést soubory POT do BMP pomocí několika řádků kódu.

Aspose.Slides for Node.js jako moderní API pro zpracování dokumentů rychle exportuje soubory POT do formátů souborů BMP. Knihovna Aspose PowerPoint vám umožňuje převést POT do BMPs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte POT na BMP pomocí Node.js" %}}
Chcete-li převést POT do BMP, budete muset vytvořit prezentaci ze souboru POT a uložit ji jako BMP.

{{% blocks/products/pf/agp/code-block title="Kód Node.js pro převod POT do BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pot");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést POT na BMP pomocí Aspose.Slides pro Node.js přes Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Chcete-li převést POT na BMP pomocí Aspose.Slides for Node.js přes Java, musíte importovat balíček do souboru JavaScript a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides pro Node.js přes Java**](https://products.aspose.com/slides/cs/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory POT v Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést POT do jiných podporovaných formátů" subTitle="Můžete také převést POT a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pot-to-tiff/" name="POT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}