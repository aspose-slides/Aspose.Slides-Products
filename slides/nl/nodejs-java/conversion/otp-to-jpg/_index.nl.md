---
title: Converteer OTP naar JPG in Node.js
url: /nl/nodejs-java/conversion/otp-to-jpg/
keywords: OTP naar JPG, Converteer OTP naar JPG, Node.js API, Node.js-bibliotheek, OTP, JPG
description: Converteer OTP naar JPG in Node.js. Gebruik de Node.js-bibliotheek-API om OTP-bestanden naar JPGs te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer OTP naar JPG in Node.js" h2="Aspose.Slides voor Node.js via Java is een krachtige en gebruiksvriendelijke bibliotheek waarmee u PowerPoint-presentaties naar verschillende formaten in Node.js kunt converteren. Het ondersteunt alle presentatie-elementen en formaten en biedt een rijke API om deze te openen en aan te passen. Hiermee kunt u uw dia's ook naar verschillende formaten exporteren voor verdere verwerking of delen." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer OTP naar JPG in Node.js" %}}

[**Aspose.Slides voor Node.js via Java**](https://products.aspose.com/slides/nl/nodejs-java/) is een krachtige Node.js-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om OTP naar JPG te converteren. Met behulp van **Aspose.Slides voor Node.js via Java** kan elke ontwikkelaar of applicatie met slechts een paar regels code bestanden van OTP naar JPG converteren.

Als moderne documentverwerkings-API exporteert Aspose.Slides voor Node.js snel OTP bestanden naar JPG bestandsformaten. Met de Aspose PowerPoint-bibliotheek kunt u OTP naar JPGs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer OTP naar JPG met Node.js" %}}
Om het bestand OTP naar JPG te converteren, moet u een presentatie maken van het bestand OTP en dit opslaan als JPG.

{{% blocks/products/pf/agp/code-block title="Node.js-code voor het converteren van OTP naar JPG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Hoe u OTP naar JPG kunt converteren met behulp van Aspose.Slides voor Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Als u OTP naar JPG wilt converteren met Aspose.Slides voor Node.js via Java, moet u het pakket in uw JavaScript-bestand importeren en een exemplaar van de klasse Presentation maken. De klasse Presentation vertegenwoordigt een PowerPoint-document en biedt methoden om de elementen ervan te openen en te manipuleren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor Node.js via Java**](https://products.aspose.com/slides/nl/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw Node.js-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden OTP in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het resultaat op als JPG bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer OTP naar andere ondersteunde formaten" subTitle="U kunt OTP ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}