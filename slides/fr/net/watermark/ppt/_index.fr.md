---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ajouter un filigrane à des présentations PPT en C#
url: /fr/net/watermark/ppt/
description: Ajoutez des filigranes texte et image à des présentations PPT en C# avec Aspose.Slides for .NET.
keywords: ajouter un filigrane à PPT, ajouter un filigrane texte à PPT, ajouter un filigrane image à PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ajouter un filigrane à une présentation PPT en C#" h2="Créez des applications .NET qui insèrent des filigranes texte ou image dans des fichiers de présentation." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ajouter un filigrane à une présentation PPT via C#" variant="code" %}}

Avec [Aspose.Slides for .NET](/slides/fr/net/), vous pouvez ajouter des filigranes texte et image à des présentations PPT. Ajoutez une forme de filigrane à un masque de diapositive pour que le filigrane apparaisse sur les diapositives qui utilisent ce masque.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane texte à PPT en C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane image à une présentation PPT en C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment ajouter un filigrane à PPT en C#" intro="Suivez ces étapes pour ajouter un filigrane texte ou image à des fichiers PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier `PPT` avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sélectionnez un masque de diapositive dans la collection `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `AddAutoShape` pour ajouter une forme de filigrane.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `AddTextFrame` pour ajouter le texte du filigrane ou utilisez `AddImage` pour un filigrane image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier filigrané avec `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Conçu avec Aspose.Slides" title="Ajouter des filigranes à des fichiers PPT en ligne" description="L'application gratuite Aspose.Slides Watermark est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Watermark" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides ajoute des filigranes avant d'écrire du code.
- Ajoutez un filigrane texte ou image à votre fichier PPT.
- Téléchargez le fichier filigrané.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les filigranes" subTitle="En C#, vous pouvez aussi ajouter des filigranes aux formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
