---
title: Konvertera PPSX till JPG i JavaScript
url: /sv/nodejs-net/conversion/ppsx-to-jpg/
keywords: PPSX till JPG, Konvertera PPSX till JPG, Node.js API, JavaScript Library, PPSX, JPG
description: Konvertera PPSX till JPG i JavaScript. Använd Node.js biblioteks-API för att konvertera PPSX-filer till JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera PPSX till JPG i JavaScript" h2="Aspose.Slides för Node.js via .NET är ett kraftfullt och lättanvänt bibliotek som låter dig konvertera PowerPoint-presentationer till olika format i JavaScript. Den stöder alla presentationselement och format och tillhandahåller ett rikt API för att komma åt och ändra dem. Det låter dig också exportera dina bilder till olika format för vidare bearbetning eller delning." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera PPSX till JPG i Node.js" %}}

[**Aspose.Slides för Node.js via .NET**](https://products.aspose.com/slides/sv/nodejs-net/) är ett kraftfullt Node.js-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera PPSX till JPG. Genom att använda **Aspose.Slides för Node.js via .NET** kan alla utvecklare eller appar konvertera PPSX till JPG-filer med bara några rader kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Node.js via .NET snabbt PPSX-filer till JPG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera PPSX till JPG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera PPSX till JPG med JavaScript" %}}
För att konvertera PPSX till JPG måste du skapa en presentation från filen PPSX och spara den som JPG.

{{% blocks/products/pf/agp/code-block title="JavaScript-kod för att konvertera PPSX till JPG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppsx");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".jpg", ImageFormat.Jpeg); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar PPSX till JPG med Aspose.Slides för Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="För att konvertera PPSX till JPG med Aspose.Slides för Node.js via .NET måste du importera paketet i din JavaScript-fil och skapa en instans av klassen Presentation. Klassen Presentation representerar ett PowerPoint-dokument och tillhandahåller metoder för att komma åt och manipulera dess element." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/sv/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Node.js-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna PPSX i Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som JPG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera PPSX till andra format som stöds" subTitle="Du kan också konvertera PPSX och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/nodejs-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}