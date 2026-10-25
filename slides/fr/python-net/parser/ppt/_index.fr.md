---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Extraire le texte de fichiers PPT avec Python
url: /fr/python-net/parser/ppt/
description: Extrayez le texte et les détails de mise en forme de présentations PPT avec Python.
keywords: analyser PPT avec Python, analyseur PPT Python, extraire des données de PPT en Python, extraire le texte de PPT avec Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Extraire le texte de présentations PPT avec Python" h2="Créez des applications Python qui extraient le texte et les détails de mise en forme de présentations PowerPoint avec Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Extraire le texte d'une présentation PPT avec Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/fr/python-net/) fournit la méthode statique [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) de `SlideUtil`. Elle renvoie les objets `TextFrame` de toute la présentation et peut inclure le texte des diapositives maîtres. L'exemple suivant extrait le texte et les détails de police associés d'une présentation PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Extraire le texte d'une présentation PPT – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment extraire le texte d'un fichier PPT avec Python" intro="Suivez ces étapes pour extraire le texte d'un fichier PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier PPT avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `SlideUtil.get_all_text_frames` en indiquant s'il faut inclure les diapositives maîtres.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez les objets `TextFrame` renvoyés.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez la collection `paragraphs` de chaque cadre de texte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez la collection `portions` de chaque paragraphe.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lisez `text` et les propriétés de mise en forme de la portion courante.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Conçu avec Aspose.Slides" title="Extraire le texte et les images en ligne" description="L'application gratuite Aspose.Slides Parser est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Parser" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides lit vos fichiers avant d'écrire du code.
- Chargez un fichier PPT et récupérez son texte et ses images.
- Téléchargez le tout dans une seule archive ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats d'analyse pris en charge" subTitle="Avec Python, vous pouvez aussi extraire le texte d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
