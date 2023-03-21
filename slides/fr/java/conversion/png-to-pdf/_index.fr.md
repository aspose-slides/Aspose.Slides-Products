---
title: Convertir PNG en PDF en Java
url: /fr/java/conversion/png-to-pdf/
keywords: PNG en PDF, Convertir PNG en PDF, API Java, Bibliothèque Java, PNG, PDF
description: Convertissez PNG en PDF en Java. Utilisez l'API de la bibliothèque Java pour convertir les fichiers PNG en PDFs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PNG en PDF en Java" h2="Bibliothèque Java haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PNG en PDF en Java" %}}

[**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir PNG en PDF. En utilisant **Aspose.Slides pour Java**, n'importe quel développeur ou application peut convertir des fichiers PNG en fichiers PDF avec seulement quelques lignes de code Java.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour Java exporte rapidement les fichiers PNG vers les formats de fichier PDF. La bibliothèque Aspose PowerPoint vous permet de convertir PNG en PDFs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir PNG en PDF en utilisant Java" %}}
Pour convertir le PNG en PDF, vous devrez créer une présentation à partir du fichier PNG et l'enregistrer sous le nom PDF.

{{% blocks/products/pf/agp/code-block title="Code Java pour convertir PNG en PDF" offSpacer="true" %}}

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir PNG en PDF à l'aide de l'API Aspose.Slides pour Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir PNG en PDF en Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers source PNG en Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertisseur en ligne gratuit" sectionDescription="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PNG vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir PNG et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}