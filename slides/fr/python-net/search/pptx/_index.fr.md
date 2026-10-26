---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Rechercher du texte dans des présentations PPTX avec Python
url: /fr/python-net/search/pptx/
description: Recherchez du texte dans des présentations PPTX avec Python et Aspose.Slides.
keywords: rechercher du texte dans un PPTX, trouver des mots dans un PPTX, rechercher dans une présentation PPTX avec Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rechercher du texte dans des présentations PPTX avec Python" h2="Créez des applications Python qui trouvent du texte dans des présentations PowerPoint avec Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rechercher du texte dans une présentation PPTX avec Python" variant="code" %}}

Avec [Aspose.Slides for Python via .NET](/slides/fr/python-net/), vous pouvez utiliser [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) pour trouver, sur chaque diapositive, les cadres de texte qui contiennent une chaîne donnée.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rechercher du texte dans une présentation PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment rechercher du texte dans un PPTX avec Python" intro="Suivez ces étapes pour rechercher du texte dans une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier PPTX avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez les diapositives et appelez [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) pour chacune d'elles.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lisez la propriété `text` de chaque cadre de texte trouvé.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Conçu avec Aspose.Slides" title="Rechercher du texte dans des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Search est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Search" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides trouve du texte avant d'écrire du code.
- Recherchez du texte brut ou des expressions régulières dans votre fichier PPTX.
- Téléchargez les résultats sous forme de fichier texte.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la recherche" subTitle="Utilisez Python pour rechercher du texte dans d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
