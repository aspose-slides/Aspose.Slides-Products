---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ajouter un filigrane à des fichiers de présentation ODP en Java
url: /fr/java/watermark/odp/
description: Ajoutez des filigranes texte et image à des présentations ODP en Java avec Aspose.Slides for Java.
keywords: ajouter un filigrane à ODP, ajouter un filigrane texte à ODP, ajouter un filigrane image à ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ajouter un filigrane à une présentation ODP en Java" h2="Créez des applications Java qui insèrent des filigranes texte ou image dans des fichiers de présentation avec des API côté serveur." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ajouter un filigrane à une présentation ODP via Java" variant="code" %}}

Avec [Aspose.Slides for Java](/slides/fr/java/), vous pouvez ajouter des filigranes texte et image à des présentations ODP. Ajoutez une forme de filigrane à un masque de diapositive pour que le filigrane apparaisse sur les diapositives qui utilisent ce masque.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane texte à ODP en Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane image à une présentation ODP en Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment ajouter un filigrane à ODP en Java" intro="Suivez ces étapes pour ajouter un filigrane texte ou image à des fichiers ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier `ODP` avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sélectionnez un masque de diapositive avec la méthode `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `addAutoShape` pour ajouter une forme de filigrane.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `addTextFrame` pour ajouter le texte du filigrane ou utilisez `addImage` pour un filigrane image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation filigranée au format ODP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Conçu avec Aspose.Slides" title="Ajouter des filigranes à des fichiers ODP en ligne" description="L'application gratuite Aspose.Slides Watermark est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers ODP." button="Ouvrir Aspose.Slides Watermark" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides ajoute des filigranes avant d'écrire du code.
- Ajoutez un filigrane texte ou image à votre fichier ODP.
- Téléchargez le fichier filigrané.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les filigranes" subTitle="En Java, vous pouvez aussi ajouter des filigranes aux formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
