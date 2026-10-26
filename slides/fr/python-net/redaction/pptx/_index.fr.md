---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Caviarder du texte dans des présentations PPTX avec Python
url: /fr/python-net/redaction/pptx/
description: Recherchez et remplacez du texte sensible dans des présentations PPTX avec Python.
keywords: caviarder un PPTX, rechercher et remplacer du texte dans un PPTX, mettre à jour une présentation PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Caviarder du texte dans des présentations PPTX avec Python" h2="Créez des applications Python qui recherchent et remplacent du texte sensible dans des présentations avec Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Caviarder du texte dans une présentation PPTX avec Python" variant="code" %}}

Avec [Aspose.Slides for Python via .NET](/slides/fr/python-net/), vous pouvez remplacer du texte sensible dans toute une présentation PPTX. Utilisez `Presentation.replace_text` avec `TextSearchOptions` pour contrôler la recherche, puis enregistrez la présentation modifiée.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Caviarder du texte dans une présentation PPTX – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.pptx") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment caviarder du texte dans une présentation PPTX avec Python" intro="Suivez ces étapes pour remplacer du texte sensible dans une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier PPTX avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) avec `TextSearchOptions` pour remplacer le texte voulu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation modifiée avec `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Conçu avec Aspose.Slides" title="Caviarder des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Redaction est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Redaction" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides recherche et remplace du texte avant d'écrire du code.
- Recherchez et remplacez du texte dans votre fichier PPTX, y compris avec des expressions régulières.
- Téléchargez le fichier caviardé.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour le caviardage" subTitle="Utilisez Python pour caviarder du texte dans d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
