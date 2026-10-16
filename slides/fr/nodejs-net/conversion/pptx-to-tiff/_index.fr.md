---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPTX en TIFF en JavaScript
url: /fr/nodejs-net/conversion/pptx-to-tiff/
keywords: PPTX en TIFF, Convertir PPTX en TIFF, API Node.js, Bibliothèque JavaScript, PPTX, TIFF
description: Convertissez PPTX en TIFF en JavaScript. Utilisez l'API de la bibliothèque Node.js pour convertir les fichiers PPTX en TIFF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PPTX en TIFF en JavaScript" h2="Aspose.Slides pour Node.js via .NET est une bibliothèque puissante et facile à utiliser qui vous permet de convertir des présentations PowerPoint en différents formats en JavaScript. Il prend en charge tous les éléments et formats de présentation et fournit une API riche pour y accéder et les modifier. Il vous permet également d'exporter vos diapositives vers différents formats pour un traitement ou un partage ultérieur." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PPTX en TIFF à l'aide de JavaScript" variant="code" %}}

Pour convertir le PPTX en TIFF, vous devrez créer une présentation à partir du fichier PPTX et l'enregistrer sous TIFF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code JavaScript pour convertir PPTX en TIFF" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptx");
try
{
    pres.save("output.tiff", SaveFormat.Tiff);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PPTX en TIFF dans Node.js" %}}

[**Aspose.Slides pour Node.js via .NET**](https://products.aspose.com/slides/fr/nodejs-net/) est une puissante bibliothèque Node.js permettant de créer et de manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de convertir PPTX en TIFF. En utilisant **Aspose.Slides pour Node.js via .NET**, n'importe quel développeur ou application peut convertir des fichiers PPTX en TIFF avec seulement quelques lignes de code.

En tant qu'API moderne de traitement de documents, Aspose.Slides pour Node.js via .NET exporte rapidement les fichiers PPTX vers les formats de fichiers TIFF. La bibliothèque Aspose PowerPoint vous permet de convertir PPTX en TIFF et de nombreux autres formats de fichiers

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PPTX en TIFF à l'aide d'Aspose.Slides pour Node.js via l'API .NET" intro="Pour convertir PPTX en TIFF à l'aide d'Aspose.Slides pour Node.js via .NET, vous devez importer le package dans votre fichier JavaScript et créer une instance de la classe Présentation. La classe Présentation représente un document PowerPoint et fournit des méthodes pour accéder et manipuler ses éléments." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [**Aspose.Slides pour Node.js via .NET**](https://products.aspose.com/slides/fr/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez les fichiers sources PPTX dans Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le résultat dans un fichier TIFF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PPTX en d'autres formats pris en charge" subTitle="Vous pouvez également convertir PPTX et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
