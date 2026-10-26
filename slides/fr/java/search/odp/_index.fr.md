---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Rechercher du texte dans des fichiers de présentation ODP avec Java
url: /fr/java/search/odp/
description: Recherchez du texte dans des présentations ODP en Java avec Aspose.Slides for Java.
keywords: rechercher des mots dans un ODP, rechercher du texte dans un ODP, rechercher le texte d'une présentation ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Rechercher du texte dans un ODP avec Java" h2="Créez des applications Java qui recherchent du texte dans des fichiers de présentation grâce à des API côté serveur." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rechercher du texte dans une présentation ODP via Java" variant="code" %}}

Avec [Aspose.Slides for Java](/slides/fr/java/), vous pouvez rechercher du texte dans des présentations ODP. Utilisez la méthode `SlideUtil.getAllTextBoxes` pour collecter les cadres de texte, puis examinez les objets `ITextFrame`, `IParagraph` et `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rechercher du texte dans une présentation ODP avec Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment rechercher du texte dans un ODP via Java" intro="Suivez ces étapes pour rechercher du texte dans une présentation ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier ODP avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `SlideUtil.getAllTextBoxes` pour collecter les cadres de texte de chaque diapositive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Examinez les objets `ITextFrame`, `IParagraph` et `IPortion` pour trouver le texte correspondant.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Conçu avec Aspose.Slides" title="Rechercher du texte dans des fichiers ODP en ligne" description="L'application gratuite Aspose.Slides Search est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers ODP." button="Ouvrir Aspose.Slides Search" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides trouve du texte avant d'écrire du code.
- Recherchez du texte brut ou des expressions régulières dans votre fichier ODP.
- Téléchargez les résultats sous forme de fichier texte.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la recherche" subTitle="Avec Java, vous pouvez également rechercher du texte dans les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
