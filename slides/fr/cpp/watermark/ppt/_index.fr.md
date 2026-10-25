---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ajouter un filigrane à des présentations PPT en C++
url: /fr/cpp/watermark/ppt/
description: Ajoutez des filigranes texte ou image à des présentations PPT en C++. Utilisez Aspose.Slides for C++ pour placer des filigranes sur les diapositives.
keywords: ajouter un filigrane à PPT, ajouter un filigrane texte à PPT, ajouter un filigrane image à PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ajouter un filigrane à une présentation PPT en C++" h2="Utilisez Aspose.Slides for C++ pour ajouter des filigranes texte ou image à des fichiers de présentation sans Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ajouter un filigrane à une présentation PPT via C++" variant="code" %}}

Aspose.Slides for C++ permet d'ajouter des filigranes texte ou image à des présentations PPT. Ajoutez une forme de filigrane au masque de diapositive avec `AddAutoShape`, ajoutez du texte avec `AddTextFrame` ou remplissez la forme avec une image chargée via `File::ReadAllBytes` et `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane texte à PPT en C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane image à une présentation PPT en C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment ajouter un filigrane à PPT en C++" intro="Suivez ces étapes pour ajouter un filigrane texte ou image à des fichiers PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPT avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sélectionnez le masque de diapositive dans la collection `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une forme de filigrane avec la méthode `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez le texte du filigrane avec la méthode `AddTextFrame` ou définissez un remplissage d'image avec `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier filigrané avec `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Conçu avec Aspose.Slides" title="Ajouter des filigranes à des fichiers PPT en ligne" description="L'application gratuite Aspose.Slides Watermark est conçue avec [Aspose.Slides for C++](https://products.aspose.com/slides/fr/cpp/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Watermark" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides ajoute des filigranes avant d'écrire du code.
- Ajoutez un filigrane texte ou image à votre fichier PPT.
- Téléchargez le fichier filigrané.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les filigranes" subTitle="En C++, vous pouvez aussi ajouter des filigranes aux formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
