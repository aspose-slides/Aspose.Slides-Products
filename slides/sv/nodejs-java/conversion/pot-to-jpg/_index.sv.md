---
title: Konvertera POT till JPG i Node.js
url: /sv/nodejs-java/conversion/pot-to-jpg/
keywords: POT till JPG, Konvertera POT till JPG, Node.js API, Node.js Library, POT, JPG
description: Konvertera POT till JPG i Node.js. Använd Node.js biblioteks-API för att konvertera POT-filer till JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera POT till JPG i Node.js" h2="Aspose.Slides för Node.js via Java är ett kraftfullt och lättanvänt bibliotek som låter dig konvertera PowerPoint-presentationer till olika format i Node.js. Den stöder alla presentationselement och format och tillhandahåller ett rikt API för att komma åt och ändra dem. Det låter dig också exportera dina bilder till olika format för vidare bearbetning eller delning." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera POT till JPG i Node.js" %}}

[**Aspose.Slides för Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/) är ett kraftfullt Node.js-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera POT till JPG. Genom att använda **Aspose.Slides för Node.js via Java** kan alla utvecklare eller applikationer konvertera POT till JPG-filer med bara några rader kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Node.js snabbt POT-filer till JPG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera POT till JPG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera POT till JPG med Node.js" %}}
För att konvertera POT till JPG måste du skapa en presentation från filen POT och spara den som JPG.

{{% blocks/products/pf/agp/code-block title="Node.js-kod för att konvertera POT till JPG" offSpacer="true" %}}

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
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".jpg");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "jpeg", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar POT till JPG med hjälp av Aspose.Slides för Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="För att konvertera POT till JPG med Aspose.Slides för Node.js via Java måste du importera paketet i din JavaScript-fil och skapa en instans av klassen Presentation. Klassen Presentation representerar ett PowerPoint-dokument och tillhandahåller metoder för att komma åt och manipulera dess element." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Node.js-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna POT i Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som JPG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera POT till andra format som stöds" subTitle="Du kan också konvertera POT och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/pot-to-tiff/" name="POT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}