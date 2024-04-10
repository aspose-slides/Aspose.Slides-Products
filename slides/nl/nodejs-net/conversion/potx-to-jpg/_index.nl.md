---
title: Converteer POTX naar JPG in JavaScript
url: /nl/nodejs-net/conversion/potx-to-jpg/
keywords: POTX naar JPG, Converteer POTX naar JPG, Node.js API, JavaScript-bibliotheek, POTX, JPG
description: Converteer POTX naar JPG in JavaScript. Gebruik de Node.js-bibliotheek-API om POTX bestanden naar JPG te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer POTX naar JPG in JavaScript" h2="Aspose.Slides voor Node.js via .NET is een krachtige en gebruiksvriendelijke bibliotheek waarmee u PowerPoint-presentaties naar verschillende formaten in JavaScript kunt converteren. Het ondersteunt alle presentatie-elementen en formaten en biedt een rijke API om deze te openen en aan te passen. Hiermee kunt u uw dia's ook naar verschillende formaten exporteren voor verdere verwerking of delen." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer POTX naar JPG in Node.js" %}}

[**Aspose.Slides voor Node.js via .NET**](https://products.aspose.com/slides/nl/nodejs-net/) is een krachtige Node.js-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om POTX naar JPG te converteren. Met **Aspose.Slides voor Node.js via .NET** kan elke ontwikkelaar of applicatie met slechts een paar regels code bestanden van POTX naar JPG converteren.

Als moderne documentverwerkings-API exporteert Aspose.Slides voor Node.js via .NET snel POTX bestanden naar JPG bestandsformaten. Met de Aspose PowerPoint-bibliotheek kunt u POTX naar JPGs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer POTX naar JPG met JavaScript" %}}
Om het bestand POTX naar JPG te converteren, moet u een presentatie maken van het bestand POTX en dit opslaan als JPG.

{{% blocks/products/pf/agp/code-block title="JavaScript-code voor het converteren van POTX naar JPG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potx");
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

{{< blocks/products/pf/feature-page-section  h2="Hoe u POTX naar JPG converteert met Aspose.Slides voor Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Als u POTX naar JPG wilt converteren met Aspose.Slides voor Node.js via .NET, moet u het pakket in uw JavaScript-bestand importeren en een exemplaar van de klasse Presentation maken. De klasse Presentation vertegenwoordigt een PowerPoint-document en biedt methoden om de elementen ervan te openen en te manipuleren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor Node.js via .NET**](https://products.aspose.com/slides/nl/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw Node.js-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden POTX in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het resultaat op als JPG bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer POTX naar andere ondersteunde formaten" subTitle="U kunt POTX ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-net/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}