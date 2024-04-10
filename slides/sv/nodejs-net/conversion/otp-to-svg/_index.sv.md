---
title: Konvertera OTP till SVG i JavaScript
url: /sv/nodejs-net/conversion/otp-to-svg/
keywords: OTP till SVG, Konvertera OTP till SVG, Node.js API, JavaScript Library, OTP, SVG
description: Konvertera OTP till SVG i JavaScript. Använd Node.js biblioteks-API för att konvertera OTP-filer till SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera OTP till SVG i JavaScript" h2="Aspose.Slides för Node.js via .NET är ett kraftfullt och lättanvänt bibliotek som låter dig konvertera PowerPoint-presentationer till olika format i JavaScript. Den stöder alla presentationselement och format och tillhandahåller ett rikt API för att komma åt och ändra dem. Det låter dig också exportera dina bilder till olika format för vidare bearbetning eller delning." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera OTP till SVG i Node.js" %}}

[**Aspose.Slides för Node.js via .NET**](https://products.aspose.com/slides/sv/nodejs-net/) är ett kraftfullt Node.js-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera OTP till SVG. Genom att använda **Aspose.Slides för Node.js via .NET** kan alla utvecklare eller appar konvertera OTP till SVG-filer med bara några rader kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Node.js via .NET snabbt OTP-filer till SVG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera OTP till SVG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera OTP till SVG med JavaScript" %}}
För att konvertera OTP till SVG måste du skapa en presentation från filen OTP och spara den som SVG.

{{% blocks/products/pf/agp/code-block title="JavaScript-kod för att konvertera OTP till SVG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.otp");
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

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar OTP till SVG med Aspose.Slides för Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="För att konvertera OTP till SVG med Aspose.Slides för Node.js via .NET måste du importera paketet i din JavaScript-fil och skapa en instans av klassen Presentation. Klassen Presentation representerar ett PowerPoint-dokument och tillhandahåller metoder för att komma åt och manipulera dess element." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/sv/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Node.js-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna OTP i Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som SVG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera OTP till andra format som stöds" subTitle="Du kan också konvertera OTP och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}