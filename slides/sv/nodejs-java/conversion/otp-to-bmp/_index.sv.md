---
title: Konvertera OTP till BMP i Node.js
url: /sv/nodejs-java/conversion/otp-to-bmp/
keywords: OTP till BMP, Konvertera OTP till BMP, Node.js API, Node.js Library, OTP, BMP
description: Konvertera OTP till BMP i Node.js. Använd Node.js biblioteks-API för att konvertera OTP-filer till BMPs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera OTP till BMP i Node.js" h2="Aspose.Slides för Node.js via Java är ett kraftfullt och lättanvänt bibliotek som låter dig konvertera PowerPoint-presentationer till olika format i Node.js. Den stöder alla presentationselement och format och tillhandahåller ett rikt API för att komma åt och ändra dem. Det låter dig också exportera dina bilder till olika format för vidare bearbetning eller delning." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera OTP till BMP i Node.js" %}}

[**Aspose.Slides för Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/) är ett kraftfullt Node.js-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera OTP till BMP. Genom att använda **Aspose.Slides för Node.js via Java** kan alla utvecklare eller applikationer konvertera OTP till BMP-filer med bara några rader kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Node.js snabbt OTP-filer till BMP-filformat. Aspose PowerPoint-bibliotek låter dig konvertera OTP till BMP och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera OTP till BMP med Node.js" %}}
För att konvertera OTP till BMP måste du skapa en presentation från filen OTP och spara den som BMP.

{{% blocks/products/pf/agp/code-block title="Node.js-kod för att konvertera OTP till BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.otp");
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

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar OTP till BMP med hjälp av Aspose.Slides för Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="För att konvertera OTP till BMP med Aspose.Slides för Node.js via Java måste du importera paketet i din JavaScript-fil och skapa en instans av klassen Presentation. Klassen Presentation representerar ett PowerPoint-dokument och tillhandahåller metoder för att komma åt och manipulera dess element." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Node.js-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna OTP i Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som BMP-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera OTP till andra format som stöds" subTitle="Du kan också konvertera OTP och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}