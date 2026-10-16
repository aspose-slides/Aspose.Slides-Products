---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PDF en PPTM dans Node.js
url: /fr/nodejs-java/conversion/pdf-to-pptm/
keywords: PDF en PPTM, Convertir PDF en PPTM, API Node.js, Bibliothèque Node.js, PDF, PPTM
description: Convertissez PDF en PPTM dans Node.js. Utilisez l'API de la bibliothèque Node.js pour convertir les fichiers PDF en PPTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PDF en PPTM dans Node.js" h2="Aspose.Slides pour Node.js via Java est une bibliothèque puissante et facile à utiliser qui vous permet de convertir des présentations PowerPoint en différents formats dans Node.js. Il prend en charge tous les éléments et formats de présentation et fournit une API riche pour y accéder et les modifier. Il vous permet également d'exporter vos diapositives vers différents formats pour un traitement ou un partage ultérieur." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PDF en PPTM à l'aide de Node.js" variant="code" %}}

Pour convertir le PDF en PPTM, vous devrez créer une présentation à partir du fichier PDF et l'enregistrer sous PPTM.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code Node.js pour convertir PDF en PPTM" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.pptm", aspose.slides.SaveFormat.Pptm);
}
finally
{
    if (pres != null) pres.dispose();
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PDF en PPTM dans Node.js" %}}

[**Aspose.Slides pour Node.js via Java**](https://products.aspose.com/slides/fr/nodejs-java/) est une puissante bibliothèque Node.js permettant de créer et de manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de convertir PDF en PPTM. En utilisant **Aspose.Slides pour Node.js via Java**, tout développeur ou application peut convertir des fichiers PDF en PPTM avec seulement quelques lignes de code.

En tant qu'API moderne de traitement de documents, Aspose.Slides pour Node.js exporte rapidement les fichiers PDF vers les formats de fichiers PPTM. La bibliothèque Aspose PowerPoint vous permet de convertir PDF en PPTM et de nombreux autres formats de fichiers

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PDF en PPTM à l'aide d'Aspose.Slides pour Node.js via l'API Java" intro="Pour convertir PDF en PPTM à l'aide d'Aspose.Slides pour Node.js via Java, vous devez importer le package dans votre fichier JavaScript et créer une instance de la classe Présentation. La classe Présentation représente un document PowerPoint et fournit des méthodes pour accéder et manipuler ses éléments." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [**Aspose.Slides pour Node.js via Java**](https://products.aspose.com/slides/fr/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez les fichiers sources PDF dans Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le résultat dans un fichier PPTM.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PDF en d'autres formats pris en charge" subTitle="Vous pouvez également convertir PDF et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
