---
title: Convertir PDF en JPG en Java
url: /fr/java/conversion/pdf-to-jpg/
keywords: PDF en JPG, Convertir PDF en JPG, API Java, Bibliothèque Java, PDF, JPG
description: Convertissez PDF en JPG en Java. Utilisez l'API de la bibliothèque Java pour convertir les fichiers PDF en JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PDF en JPG en Java" h2="Bibliothèque Java haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PDF en JPG en Java" %}}

[**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir PDF en JPG. En utilisant **Aspose.Slides pour Java**, n'importe quel développeur ou application peut convertir des fichiers PDF en fichiers JPG avec seulement quelques lignes de code Java.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour Java exporte rapidement les fichiers PDF vers les formats de fichier JPG. La bibliothèque Aspose PowerPoint vous permet de convertir PDF en JPGs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir PDF en JPG en utilisant Java" %}}
Pour convertir le PDF en JPG, vous devrez créer une présentation à partir du fichier PDF et l'enregistrer sous le nom JPG.

{{% blocks/products/pf/agp/code-block title="Code Java pour convertir PDF en JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    pres.getSlides().addFromPdf("InputPDF.pdf");
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir PDF en JPG à l'aide de l'API Aspose.Slides pour Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir PDF en JPG en Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers source PDF en Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PDF vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir PDF et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}