---
title: Convertir PPSX en SVG dans Node.js
url: /fr/nodejs-java/conversion/ppsx-to-svg/
keywords: PPSX en SVG, Convertir PPSX en SVG, API Node.js, Bibliothèque Node.js, PPSX, SVG
description: Convertissez PPSX en SVG dans Node.js. Utilisez l'API de la bibliothèque Node.js pour convertir les fichiers PPSX en SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PPSX en SVG dans Node.js" h2="Aspose.Slides pour Node.js via Java est une bibliothèque puissante et facile à utiliser qui vous permet de convertir des présentations PowerPoint en différents formats dans Node.js. Il prend en charge tous les éléments et formats de présentation et fournit une API riche pour y accéder et les modifier. Il vous permet également d'exporter vos diapositives vers différents formats pour un traitement ou un partage ultérieur." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PPSX en SVG dans Node.js" %}}

[**Aspose.Slides pour Node.js via Java**](https://products.aspose.com/slides/fr/nodejs-java/) est une puissante bibliothèque Node.js permettant de créer et de manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de convertir PPSX en SVG. En utilisant **Aspose.Slides pour Node.js via Java**, tout développeur ou application peut convertir des fichiers PPSX en SVG avec seulement quelques lignes de code.

En tant qu'API moderne de traitement de documents, Aspose.Slides pour Node.js exporte rapidement les fichiers PPSX vers les formats de fichiers SVG. La bibliothèque Aspose PowerPoint vous permet de convertir PPSX en SVG et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir PPSX en SVG à l'aide de Node.js" %}}
Pour convertir le PPSX en SVG, vous devrez créer une présentation à partir du fichier PPSX et l'enregistrer sous SVG.

{{% blocks/products/pf/agp/code-block title="Code Node.js pour convertir PPSX en SVG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsx");
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir PPSX en SVG à l'aide d'Aspose.Slides pour Node.js via l'API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Pour convertir PPSX en SVG à l'aide d'Aspose.Slides pour Node.js via Java, vous devez importer le package dans votre fichier JavaScript et créer une instance de la classe Présentation. La classe Présentation représente un document PowerPoint et fournit des méthodes pour accéder et manipuler ses éléments." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour Node.js via Java**](https://products.aspose.com/slides/fr/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers sources PPSX dans Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat dans un fichier SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PPSX en d'autres formats pris en charge" subTitle="Vous pouvez également convertir PPSX et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}