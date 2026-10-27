---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 360
title: Supprimer les annotations d'un PPTX avec Java
url: /fr/java/annotation/pptx/ 
description: Supprimez les commentaires et les auteurs de commentaires des présentations PPTX en Java avec Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Supprimer les commentaires et les auteurs de commentaires d'un PPTX en Java" h2="Utilisez Aspose.Slides for Java pour supprimer les commentaires et les auteurs de commentaires des fichiers de présentation." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Supprimer les commentaires d'un PPTX via Java" variant="code" %}}

Aspose.Slides for Java vous permet de supprimer les commentaires et les auteurs de commentaires des présentations PPTX. Chargez un fichier avec la classe `Presentation`, parcourez les objets `ICommentAuthor` obtenus avec `getCommentAuthors`, effacez leurs commentaires et enregistrez la présentation mise à jour.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer les annotations d'un PPTX – Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment supprimer les commentaires d'un PPTX via Java" intro="Suivez ces étapes pour supprimer les commentaires et les auteurs de commentaires d'une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez Aspose.Slides for Java. Consultez [Installation](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPTX avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez les objets `ICommentAuthor` obtenus avec `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Effacez les commentaires de chaque auteur avec `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Videz la collection des auteurs de commentaires et enregistrez le fichier PPTX mis à jour.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Conçu avec Aspose.Slides" title="Supprimer les commentaires d'un PPTX en ligne" description="L'application gratuite Aspose.Slides Annotation est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Annotation" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides supprime les commentaires avant d'écrire du code.
- Supprimez tous les commentaires de votre fichier PPTX.
- Téléchargez le fichier nettoyé.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les annotations" subTitle="Avec Java, vous pouvez également supprimer les annotations d'autres formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
