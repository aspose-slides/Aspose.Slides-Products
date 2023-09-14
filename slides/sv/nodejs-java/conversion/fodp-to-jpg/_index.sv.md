---
title: Konvertera FODP till JPG i Node.js
url: /sv/nodejs-java/conversion/fodp-to-jpg/
keywords: FODP till JPG, Konvertera FODP till JPG, Node.js API, Node.js Library, FODP, JPG
description: Konvertera FODP till JPG i Node.js. Använd Node.js biblioteks-API för att konvertera FODP-filer till JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera FODP till JPG i Node.js" h2="Aspose.Slides för Node.js via Java är ett kraftfullt och lättanvänt bibliotek som låter dig konvertera PowerPoint-presentationer till olika format i Node.js. Den stöder alla presentationselement och format och tillhandahåller ett rikt API för att komma åt och ändra dem. Det låter dig också exportera dina bilder till olika format för vidare bearbetning eller delning." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera FODP till JPG i Node.js" %}}

[**Aspose.Slides för Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/) är ett kraftfullt Node.js-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera FODP till JPG. Genom att använda **Aspose.Slides för Node.js via Java** kan alla utvecklare eller applikationer konvertera FODP till JPG-filer med bara några rader kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Node.js snabbt FODP-filer till JPG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera FODP till JPG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera FODP till JPG med Node.js" %}}
För att konvertera FODP till JPG måste du skapa en presentation från filen FODP och spara den som JPG.

{{% blocks/products/pf/agp/code-block title="Node.js-kod för att konvertera FODP till JPG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.fodp");
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

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar FODP till JPG med hjälp av Aspose.Slides för Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="För att konvertera FODP till JPG med Aspose.Slides för Node.js via Java måste du importera paketet i din JavaScript-fil och skapa en instans av klassen Presentation. Klassen Presentation representerar ett PowerPoint-dokument och tillhandahåller metoder för att komma åt och manipulera dess element." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Node.js-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna FODP i Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som JPG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera FODP till andra format som stöds" subTitle="Du kan också konvertera FODP och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}