---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Supprimer les annotations d'un PPT avec .NET
url: /fr/net/annotation/ppt/ 
description: Supprimez les commentaires et les auteurs de commentaires des présentations PPT en C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Supprimer les commentaires et les auteurs de commentaires d'un PPT en C#" h2="Créez des applications .NET qui manipulent les commentaires et les auteurs des fichiers de présentation grâce à des API côté serveur." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Supprimer les commentaires d'un PPT via C#" variant="code" %}}

Utilisez [Aspose.Slides for .NET](/slides/fr/net/) pour supprimer les commentaires et les auteurs de commentaires des fichiers de présentation PPT. L'exemple ci-dessous vide la collection `Comments` de chaque auteur, puis la collection `CommentAuthors` de la présentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer les annotations d'un PPT – C#" >}}
```cs
using var presentation = new Presentation("example.ppt");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment supprimer les commentaires d'un PPT via C#" intro="Suivez ces étapes pour supprimer les commentaires et les auteurs de commentaires d'une présentation PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez Aspose.Slides for .NET. Consultez [Installation](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPT avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez la collection `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Videz la collection `Comments` de chaque auteur de commentaires.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Videz la collection `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation mise à jour avec `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Conçu avec Aspose.Slides" title="Supprimer les commentaires d'un PPT en ligne" description="L'application gratuite Aspose.Slides Annotation est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Annotation" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides supprime les commentaires avant d'écrire du code.
- Supprimez tous les commentaires de votre fichier PPT.
- Téléchargez le fichier nettoyé.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les annotations" subTitle="Avec C#, vous pouvez également supprimer les annotations d'autres formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
