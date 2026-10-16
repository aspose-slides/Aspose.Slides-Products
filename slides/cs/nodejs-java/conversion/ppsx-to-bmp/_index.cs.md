---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPSX na BMP v Node.js
url: /cs/nodejs-java/conversion/ppsx-to-bmp/
keywords: PPSX do BMP, Převést PPSX do BMP, Node.js API, Node.js Library, PPSX, BMP
description: Převeďte PPSX na BMP v Node.js. K převodu souborů PPSX na BMP použijte rozhraní API knihovny Node.js
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PPSX na BMP v Node.js" h2="Aspose.Slides for Node.js přes Javu je výkonná a snadno použitelná knihovna, která vám umožňuje převádět PowerPointové prezentace do různých formátů v Node.js. Podporuje všechny prezentační prvky a formáty a poskytuje bohaté API pro přístup a úpravu. Umožňuje také exportovat snímky do různých formátů pro další zpracování nebo sdílení." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PPSX na BMP pomocí Node.js" variant="code" %}}

Chcete-li převést PPSX do BMP, budete muset vytvořit prezentaci ze souboru PPSX a uložit ji jako BMP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kód Node.js pro převod PPSX do BMP" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsx");
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PPSX na BMP v Node.js" %}}

[**Aspose.Slides pro Node.js přes Javu**](https://products.aspose.com/slides/cs/nodejs-java/) je výkonná knihovna Node.js pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu PPSX do BMP. Pomocí **Aspose.Slides for Node.js přes Java** může každý vývojář nebo aplikace převést soubory PPSX do BMP pomocí několika řádků kódu.

Aspose.Slides for Node.js jako moderní API pro zpracování dokumentů rychle exportuje soubory PPSX do formátů souborů BMP. Knihovna Aspose PowerPoint vám umožňuje převést PPSX do BMPs a mnoho dalších formátů souborů

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PPSX na BMP pomocí Aspose.Slides pro Node.js přes Java API" intro="Chcete-li převést PPSX na BMP pomocí Aspose.Slides for Node.js přes Java, musíte importovat balíček do souboru JavaScript a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte [**Aspose.Slides pro Node.js přes Java**](https://products.aspose.com/slides/cs/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete zdrojové soubory PPSX v Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložit výsledek jako soubor BMP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Převést PPSX do jiných podporovaných formátů" subTitle="Můžete také převést PPSX a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/nodejs-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
