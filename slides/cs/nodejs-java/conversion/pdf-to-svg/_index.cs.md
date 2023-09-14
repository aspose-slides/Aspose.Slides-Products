---
title: Převeďte PDF na SVG v Node.js
url: /cs/nodejs-java/conversion/pdf-to-svg/
keywords: PDF do SVG, Převést PDF do SVG, Node.js API, Node.js Library, PDF, SVG
description: Převeďte PDF na SVG v Node.js. K převodu souborů PDF na SVG použijte rozhraní API knihovny Node.js
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte PDF na SVG v Node.js" h2="Aspose.Slides for Node.js přes Javu je výkonná a snadno použitelná knihovna, která vám umožňuje převádět PowerPointové prezentace do různých formátů v Node.js. Podporuje všechny prezentační prvky a formáty a poskytuje bohaté API pro přístup a úpravu. Umožňuje také exportovat snímky do různých formátů pro další zpracování nebo sdílení." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PDF na SVG v Node.js" %}}

[**Aspose.Slides pro Node.js přes Javu**](https://products.aspose.com/slides/cs/nodejs-java/) je výkonná knihovna Node.js pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu PDF do SVG. Pomocí **Aspose.Slides for Node.js přes Java** může každý vývojář nebo aplikace převést soubory PDF do SVG pomocí několika řádků kódu.

Aspose.Slides for Node.js jako moderní API pro zpracování dokumentů rychle exportuje soubory PDF do formátů souborů SVG. Knihovna Aspose PowerPoint vám umožňuje převést PDF do SVGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte PDF na SVG pomocí Node.js" %}}
Chcete-li převést PDF do SVG, budete muset vytvořit prezentaci ze souboru PDF a uložit ji jako SVG.

{{% blocks/products/pf/agp/code-block title="Kód Node.js pro převod PDF do SVG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést PDF na SVG pomocí Aspose.Slides pro Node.js přes Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Chcete-li převést PDF na SVG pomocí Aspose.Slides for Node.js přes Java, musíte importovat balíček do souboru JavaScript a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides pro Node.js přes Java**](https://products.aspose.com/slides/cs/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory PDF v Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést PDF do jiných podporovaných formátů" subTitle="Můžete také převést PDF a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}