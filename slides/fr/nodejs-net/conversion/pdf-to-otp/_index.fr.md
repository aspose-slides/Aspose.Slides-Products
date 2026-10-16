---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PDF en OTP en JavaScript
url: /fr/nodejs-net/conversion/pdf-to-otp/
keywords: PDF en OTP, Convertir PDF en OTP, API Node.js, Bibliothèque JavaScript, PDF, OTP
description: Convertissez PDF en OTP en JavaScript. Utilisez l'API de la bibliothèque Node.js pour convertir les fichiers PDF en OTP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PDF en OTP en JavaScript" h2="Aspose.Slides pour Node.js via .NET est une bibliothèque puissante et facile à utiliser qui vous permet de convertir des présentations PowerPoint en différents formats en JavaScript. Il prend en charge tous les éléments et formats de présentation et fournit une API riche pour y accéder et les modifier. Il vous permet également d'exporter vos diapositives vers différents formats pour un traitement ou un partage ultérieur." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PDF en OTP à l'aide de JavaScript" variant="code" %}}

Pour convertir le PDF en OTP, vous devrez créer une présentation à partir du fichier PDF et l'enregistrer sous OTP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code JavaScript pour convertir PDF en OTP" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try
{
    pres.slides.removeAt(0);
    var slides = pres.slides.addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.otp", SaveFormat.Otp);
}
finally
{
    if (pres != null) pres.dispose();
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PDF en OTP dans Node.js" %}}

[**Aspose.Slides pour Node.js via .NET**](https://products.aspose.com/slides/fr/nodejs-net/) est une puissante bibliothèque Node.js permettant de créer et de manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de convertir PDF en OTP. En utilisant **Aspose.Slides pour Node.js via .NET**, n'importe quel développeur ou application peut convertir des fichiers PDF en OTP avec seulement quelques lignes de code.

En tant qu'API moderne de traitement de documents, Aspose.Slides pour Node.js via .NET exporte rapidement les fichiers PDF vers les formats de fichiers OTP. La bibliothèque Aspose PowerPoint vous permet de convertir PDF en OTP et de nombreux autres formats de fichiers

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PDF en OTP à l'aide d'Aspose.Slides pour Node.js via l'API .NET" intro="Pour convertir PDF en OTP à l'aide d'Aspose.Slides pour Node.js via .NET, vous devez importer le package dans votre fichier JavaScript et créer une instance de la classe Présentation. La classe Présentation représente un document PowerPoint et fournit des méthodes pour accéder et manipuler ses éléments." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [**Aspose.Slides pour Node.js via .NET**](https://products.aspose.com/slides/fr/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez les fichiers sources PDF dans Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le résultat dans un fichier OTP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PDF en d'autres formats pris en charge" subTitle="Vous pouvez également convertir PDF et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
