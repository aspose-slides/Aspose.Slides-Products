---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Caviarder des fichiers de présentation ODP avec Java
url: /fr/java/redaction/odp/
description: Recherchez et remplacez du texte dans des présentations ODP en Java avec Aspose.Slides for Java.
keywords: caviarder un ODP, rechercher et remplacer du texte dans un ODP, mettre à jour une présentation ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Caviarder un ODP avec Java" h2="Créez des applications Java qui recherchent et remplacent du texte dans des fichiers de présentation grâce à des API côté serveur." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Caviarder une présentation ODP via Java" variant="code" %}}

Avec [Aspose.Slides for Java](/slides/fr/java/), vous pouvez rechercher et remplacer du texte dans des présentations ODP. Utilisez la méthode `SlideUtil.findAndReplaceText` pour parcourir la présentation et remplacer le texte correspondant par une nouvelle valeur.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Caviarder une présentation ODP avec Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment caviarder un ODP via Java" intro="Suivez ces étapes pour caviarder une présentation ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier ODP avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `SlideUtil.findAndReplaceText` pour rechercher et remplacer du texte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation mise à jour avec `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Conçu avec Aspose.Slides" title="Caviarder des fichiers ODP en ligne" description="L'application gratuite Aspose.Slides Redaction est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers ODP." button="Ouvrir Aspose.Slides Redaction" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides recherche et remplace du texte avant d'écrire du code.
- Recherchez et remplacez du texte dans votre fichier ODP, y compris avec des expressions régulières.
- Téléchargez le fichier caviardé.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour le caviardage" subTitle="Avec Java, vous pouvez également caviarder les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
