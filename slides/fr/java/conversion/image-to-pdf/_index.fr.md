---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir Image en PDF en Java
url: /fr/java/conversion/image-to-pdf/
keywords: Image en PDF, Convertir Image en PDF, API Java, Bibliothèque Java, Image, PDF
description: Convertissez Image en PDF en Java. Utilisez l'API de la bibliothèque Java pour convertir les fichiers Image en PDFs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir Image en PDF en Java" h2="Bibliothèque Java haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir Image en PDF en utilisant Java" variant="code" %}}

Pour convertir le Image en PDF, vous devrez créer une présentation à partir du fichier Image et l'enregistrer sous le nom PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code Java pour convertir Image en PDF" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir Image en PDF en Java" %}}

[**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir Image en PDF. En utilisant **Aspose.Slides pour Java**, n'importe quel développeur ou application peut convertir des fichiers Image en fichiers PDF avec seulement quelques lignes de code Java.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour Java exporte rapidement les fichiers Image vers les formats de fichier PDF. La bibliothèque Aspose PowerPoint vous permet de convertir Image en PDFs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir Image en PDF à l'aide de l'API Aspose.Slides pour Java" intro="Voici les étapes pour convertir Image en PDF en Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez les fichiers source Image en Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le résultat en tant que fichier PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Conçu avec Aspose.Slides" title="Convertir Image en PDF en ligne" description="L'application gratuite Aspose.Slides Conversion est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers Image." button="Ouvrir Aspose.Slides Conversion" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" upload="Déposez ou importez votre fichier" saveAs="Enregistrer sous" convert="Convertir" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Découvrez comment Aspose.Slides convertit les fichiers avant d'écrire du code.
- Téléchargez des fichiers Image et enregistrez-les au format PDF.
- Téléchargez le résultat ou convertissez d'autres fichiers.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir Image vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir Image et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
