---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Rechercher du texte dans des fichiers de présentation PPTX avec .NET
url: /fr/net/search/pptx/
description: Code source C# pour rechercher du texte dans des présentations PPTX.
keywords: Rechercher du texte dans un PPTX, trouver du texte dans un PPTX, rechercher le texte d'une présentation PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rechercher du texte dans des fichiers PPTX avec C#" h2="Créez des applications .NET qui trouvent du texte dans des présentations grâce à des API côté serveur." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rechercher du texte dans une présentation PPTX avec C#" variant="code" %}}

Avec [Aspose.Slides for .NET](/slides/fr/net/), vous pouvez rechercher du texte dans une présentation PPTX. Récupérez les cadres de texte d'une diapositive avec `SlideUtil.GetAllTextBoxes`, puis examinez leurs valeurs `Text` pour trouver l'expression voulue.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rechercher du texte dans une présentation PPTX avec C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment rechercher du texte dans une présentation PPTX avec C#" intro="Suivez ces étapes pour rechercher du texte dans une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPTX avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Récupérez la diapositive voulue dans `Presentation.Slides` et affectez-la à une variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Récupérez ses cadres de texte avec [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vérifiez si la valeur `Text` de chaque cadre contient l'expression voulue.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Conçu avec Aspose.Slides" title="Rechercher du texte dans des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Search est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Search" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides trouve du texte avant d'écrire du code.
- Recherchez du texte brut ou des expressions régulières dans votre fichier PPTX.
- Téléchargez les résultats sous forme de fichier texte.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la recherche" subTitle="Avec C#, vous pouvez également rechercher du texte dans les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
