---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera OTP till SVG i Node.js
url: /sv/nodejs-java/conversion/otp-to-svg/
keywords: OTP till SVG, Konvertera OTP till SVG, Node.js API, Node.js Library, OTP, SVG
description: Konvertera OTP till SVG i Node.js. Använd Node.js biblioteks-API för att konvertera OTP-filer till SVGs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera OTP till SVG i Node.js" h2="Aspose.Slides för Node.js via Java är ett kraftfullt och lättanvänt bibliotek som låter dig konvertera PowerPoint-presentationer till olika format i Node.js. Den stöder alla presentationselement och format och tillhandahåller ett rikt API för att komma åt och ändra dem. Det låter dig också exportera dina bilder till olika format för vidare bearbetning eller delning." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera OTP till SVG med Node.js" variant="code" %}}

För att konvertera OTP till SVG måste du skapa en presentation från filen OTP och spara den som SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js-kod för att konvertera OTP till SVG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.otp");
try
{
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera OTP till SVG i Node.js" %}}

[**Aspose.Slides för Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/) är ett kraftfullt Node.js-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera OTP till SVG. Genom att använda **Aspose.Slides för Node.js via Java** kan alla utvecklare eller applikationer konvertera OTP till SVG-filer med bara några rader kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Node.js snabbt OTP-filer till SVG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera OTP till SVG och många andra filformat

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar OTP till SVG med hjälp av Aspose.Slides för Node.js via Java API" intro="För att konvertera OTP till SVG med Aspose.Slides för Node.js via Java måste du importera paketet i din JavaScript-fil och skapa en instans av klassen Presentation. Klassen Presentation representerar ett PowerPoint-dokument och tillhandahåller metoder för att komma åt och manipulera dess element." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera [**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/sv/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en biblioteksreferens (importera biblioteket) till ditt Node.js-projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna källfilerna OTP i Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara resultatet som SVG-fil.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertera OTP till andra format som stöds" subTitle="Du kan också konvertera OTP och spara till andra filformat. Se alla format som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/nodejs-java/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
