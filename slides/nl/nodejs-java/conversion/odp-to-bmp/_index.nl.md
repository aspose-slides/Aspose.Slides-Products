---
title: Converteer ODP naar BMP in Node.js
url: /nl/nodejs-java/conversion/odp-to-bmp/
keywords: ODP naar BMP, Converteer ODP naar BMP, Node.js API, Node.js-bibliotheek, ODP, BMP
description: Converteer ODP naar BMP in Node.js. Gebruik de Node.js-bibliotheek-API om ODP-bestanden naar BMPs te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer ODP naar BMP in Node.js" h2="Aspose.Slides voor Node.js via Java is een krachtige en gebruiksvriendelijke bibliotheek waarmee u PowerPoint-presentaties naar verschillende formaten in Node.js kunt converteren. Het ondersteunt alle presentatie-elementen en formaten en biedt een rijke API om deze te openen en aan te passen. Hiermee kunt u uw dia's ook naar verschillende formaten exporteren voor verdere verwerking of delen." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer ODP naar BMP in Node.js" %}}

[**Aspose.Slides voor Node.js via Java**](https://products.aspose.com/slides/nl/nodejs-java/) is een krachtige Node.js-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om ODP naar BMP te converteren. Met behulp van **Aspose.Slides voor Node.js via Java** kan elke ontwikkelaar of applicatie met slechts een paar regels code bestanden van ODP naar BMP converteren.

Als moderne documentverwerkings-API exporteert Aspose.Slides voor Node.js snel ODP bestanden naar BMP bestandsformaten. Met de Aspose PowerPoint-bibliotheek kunt u ODP naar BMPs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer ODP naar BMP met Node.js" %}}
Om het bestand ODP naar BMP te converteren, moet u een presentatie maken van het bestand ODP en dit opslaan als BMP.

{{% blocks/products/pf/agp/code-block title="Node.js-code voor het converteren van ODP naar BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.odp");
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

{{< blocks/products/pf/feature-page-section  h2="Hoe u ODP naar BMP kunt converteren met behulp van Aspose.Slides voor Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Als u ODP naar BMP wilt converteren met Aspose.Slides voor Node.js via Java, moet u het pakket in uw JavaScript-bestand importeren en een exemplaar van de klasse Presentation maken. De klasse Presentation vertegenwoordigt een PowerPoint-document en biedt methoden om de elementen ervan te openen en te manipuleren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor Node.js via Java**](https://products.aspose.com/slides/nl/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw Node.js-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden ODP in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het resultaat op als BMP bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer ODP naar andere ondersteunde formaten" subTitle="U kunt ODP ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-png/" name="ODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/nodejs-java/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}