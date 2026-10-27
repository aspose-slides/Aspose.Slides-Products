---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Supprimer les commentaires d'un PPT en Python
url: /fr/python-net/annotation/ppt/ 
description: Supprimez les commentaires et les auteurs de commentaires des présentations PPT en Python avec Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Supprimer les commentaires et les auteurs de commentaires d'un PPT en Python" h2="Utilisez Aspose.Slides for Python via .NET pour supprimer les commentaires d'une présentation et leurs auteurs." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Supprimer les commentaires d'un PPT via Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/fr/python-net/) donne accès aux commentaires et aux auteurs de commentaires stockés dans une présentation PPT. Chargez le fichier avec `Presentation`, videz la collection `comments` de chaque auteur, videz `comment_authors` et enregistrez le résultat au format PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer les commentaires d'un PPT en Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment supprimer les commentaires d'un PPT via Python" intro="Suivez ces étapes pour supprimer tous les commentaires et auteurs de commentaires d'une présentation PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier PPT avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez `comment_authors` et videz la collection `comments` de chaque auteur.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Videz la collection `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `save` avec `SaveFormat.PPT` pour écrire la présentation PPT mise à jour.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Conçu avec Aspose.Slides" title="Supprimer les commentaires d'un PPT en ligne" description="L'application gratuite Aspose.Slides Annotation est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Annotation" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides supprime les commentaires avant d'écrire du code.
- Supprimez tous les commentaires de votre fichier PPT.
- Téléchargez le fichier nettoyé.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les annotations" subTitle="Avec Python, vous pouvez également supprimer les annotations d'autres formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
