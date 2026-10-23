---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Modifier PPT en C#
url: /fr/net/editor/ppt/
keywords: Modifier PPT, Modifier PowerPoint, PPT, PowerPoint, API C#, Bibliothèque .NET
description: Modifier PPT en C#. Utiliser l'API de la bibliothèque .NET pour modifier la présentation PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifier PPT en C#" h2="Puissante API .NET multiplateforme pour l'édition de PPT à l'aide de code C# sur les plates-formes NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier PPT en C#" variant="code" %}}

En utilisant [**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/), vous pouvez ajouter une nouvelle ligne de texte à un document PPT avec seulement quelques lignes de code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code C# pour l'édition de PPT" >}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier le PPT à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/) est une puissante bibliothèque .NET utilisée pour manipuler et modifier des présentations. Vous pouvez modifier une présentation PPT en y ajoutant une nouvelle ligne de texte.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment éditer un PPT en C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez **Aspose.Slides pour .NET**. Voir [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez la bibliothèque comme référence dans votre projet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez une instance de la classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez la présentation PPT que vous souhaitez modifier.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une nouvelle ligne de texte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier PowerPoint modifié.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Conçu avec Aspose.Slides" title="Modifiez des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Editor est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Editor" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides traite vos fichiers avant d'écrire du code.
- Chargez vos fichiers PPTX et modifiez-les instantanément.
- Enregistrez et téléchargez le fichier modifié.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Modifier d'autres fichiers" subTitle="Vous pouvez également modifier des fichiers dans d'autres formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
