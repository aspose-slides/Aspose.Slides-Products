---
title: Convertir POTM en BMP dans Node.js
url: /fr/nodejs-java/conversion/potm-to-bmp/
keywords: POTM en BMP, Convertir POTM en BMP, API Node.js, Bibliothèque Node.js, POTM, BMP
description: Convertissez POTM en BMP dans Node.js. Utilisez l'API de la bibliothèque Node.js pour convertir les fichiers POTM en BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir POTM en BMP dans Node.js" h2="Aspose.Slides pour Node.js via Java est une bibliothèque puissante et facile à utiliser qui vous permet de convertir des présentations PowerPoint en différents formats dans Node.js. Il prend en charge tous les éléments et formats de présentation et fournit une API riche pour y accéder et les modifier. Il vous permet également d'exporter vos diapositives vers différents formats pour un traitement ou un partage ultérieur." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir POTM en BMP dans Node.js" %}}

[**Aspose.Slides pour Node.js via Java**](https://products.aspose.com/slides/fr/nodejs-java/) est une puissante bibliothèque Node.js permettant de créer et de manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de convertir POTM en BMP. En utilisant **Aspose.Slides pour Node.js via Java**, tout développeur ou application peut convertir des fichiers POTM en BMP avec seulement quelques lignes de code.

En tant qu'API moderne de traitement de documents, Aspose.Slides pour Node.js exporte rapidement les fichiers POTM vers les formats de fichiers BMP. La bibliothèque Aspose PowerPoint vous permet de convertir POTM en BMP et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir POTM en BMP à l'aide de Node.js" %}}
Pour convertir le POTM en BMP, vous devrez créer une présentation à partir du fichier POTM et l'enregistrer sous BMP.

{{% blocks/products/pf/agp/code-block title="Code Node.js pour convertir POTM en BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potm");
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

{{< blocks/products/pf/feature-page-section  h2="Comment convertir POTM en BMP à l'aide d'Aspose.Slides pour Node.js via l'API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Pour convertir POTM en BMP à l'aide d'Aspose.Slides pour Node.js via Java, vous devez importer le package dans votre fichier JavaScript et créer une instance de la classe Présentation. La classe Présentation représente un document PowerPoint et fournit des méthodes pour accéder et manipuler ses éléments." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour Node.js via Java**](https://products.aspose.com/slides/fr/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers sources POTM dans Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat dans un fichier BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir POTM en d'autres formats pris en charge" subTitle="Vous pouvez également convertir POTM et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-svg/" name="POTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/nodejs-java/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}