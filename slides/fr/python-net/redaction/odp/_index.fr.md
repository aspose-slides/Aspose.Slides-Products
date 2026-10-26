---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Caviarder du texte dans des présentations ODP avec Python
url: /fr/python-net/redaction/odp/
description: Recherchez et remplacez du texte sensible dans des présentations ODP avec Python.
keywords: caviarder un ODP, rechercher et remplacer du texte dans un ODP, mettre à jour une présentation ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Caviarder du texte dans des présentations ODP avec Python" h2="Créez des applications Python qui recherchent et remplacent du texte sensible dans des présentations avec Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Caviarder du texte dans une présentation ODP avec Python" variant="code" %}}

Avec [Aspose.Slides for Python via .NET](/slides/fr/python-net/), vous pouvez remplacer du texte sensible dans toute une présentation ODP. Utilisez `Presentation.replace_text` avec `TextSearchOptions` pour contrôler la recherche, puis enregistrez la présentation modifiée.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Caviarder du texte dans une présentation ODP – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.odp") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment caviarder du texte dans une présentation ODP avec Python" intro="Suivez ces étapes pour remplacer du texte sensible dans une présentation ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier ODP avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) avec `TextSearchOptions` pour remplacer le texte voulu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation modifiée avec `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Conçu avec Aspose.Slides" title="Caviarder des fichiers ODP en ligne" description="L'application gratuite Aspose.Slides Redaction est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers ODP." button="Ouvrir Aspose.Slides Redaction" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides recherche et remplace du texte avant d'écrire du code.
- Recherchez et remplacez du texte dans votre fichier ODP, y compris avec des expressions régulières.
- Téléchargez le fichier caviardé.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour le caviardage" subTitle="Utilisez Python pour caviarder du texte dans d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
