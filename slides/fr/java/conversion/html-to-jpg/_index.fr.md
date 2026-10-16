---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir HTML en JPG en Java
url: /fr/java/conversion/html-to-jpg/
keywords: HTML en JPG, Convertir HTML en JPG, API Java, Bibliothèque Java, HTML, JPG
description: Convertissez HTML en JPG en Java. Utilisez l'API de la bibliothèque Java pour convertir les fichiers HTML en JPGs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir HTML en JPG en Java" h2="Bibliothèque Java haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir HTML en JPG en utilisant Java" variant="code" %}}

Pour convertir le HTML en JPG, vous devrez créer une présentation à partir du fichier HTML et l'enregistrer sous le nom JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code Java pour convertir HTML en JPG" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream tr = new FileInputStream("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        IImage image = slide.getImage(size);
        image.save("image_java_" + index + ".jpg", ImageFormat.Jpeg);
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir HTML en JPG en Java" %}}

[**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir HTML en JPG. En utilisant **Aspose.Slides pour Java**, n'importe quel développeur ou application peut convertir des fichiers HTML en fichiers JPG avec seulement quelques lignes de code Java.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour Java exporte rapidement les fichiers HTML vers les formats de fichier JPG. La bibliothèque Aspose PowerPoint vous permet de convertir HTML en JPGs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir HTML en JPG à l'aide de l'API Aspose.Slides pour Java" intro="Voici les étapes pour convertir HTML en JPG en Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez les fichiers source HTML en Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le résultat en tant que fichier JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertisseur en ligne gratuit"
  description="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir HTML vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir HTML et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
