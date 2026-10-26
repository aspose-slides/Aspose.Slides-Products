---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Rechercher du texte dans des présentations PPTX avec C++
url: /fr/cpp/search/pptx/
description: Recherchez du texte dans des présentations PPTX en C++. Utilisez Aspose.Slides for C++ pour trouver du texte dans des fichiers de présentation.
keywords: rechercher des mots dans un PPTX, trouver du texte dans un PPTX, rechercher le texte d'une présentation PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rechercher du texte dans un PPTX avec C++" h2="Utilisez Aspose.Slides for C++ pour trouver du texte dans des fichiers de présentation sans Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rechercher du texte dans une présentation PPTX via C++" variant="code" %}}

Aspose.Slides for C++ vous permet de rechercher du texte dans des présentations PPTX. Utilisez `SlideUtil::GetAllTextBoxes` pour collecter les cadres de texte d'une diapositive, puis vérifiez si leur texte contient l'expression voulue.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rechercher du texte dans une présentation PPTX avec C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment rechercher du texte dans un PPTX via C++" intro="Suivez ces étapes pour rechercher du texte dans une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPTX avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Récupérez la diapositive voulue avec `Presentation::get_Slides` et obtenez ses cadres de texte avec [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vérifiez si le texte de chaque cadre contient l'expression voulue.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Conçu avec Aspose.Slides" title="Rechercher du texte dans des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Search est conçue avec [Aspose.Slides for C++](https://products.aspose.com/slides/fr/cpp/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Search" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides trouve du texte avant d'écrire du code.
- Recherchez du texte brut ou des expressions régulières dans votre fichier PPTX.
- Téléchargez les résultats sous forme de fichier texte.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la recherche" subTitle="Avec C++, vous pouvez également rechercher du texte dans les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
