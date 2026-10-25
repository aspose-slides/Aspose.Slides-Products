---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Watermerk toevoegen aan PPT-presentatiebestanden met Java
url: /nl/java/watermark/ppt/
description: Voeg tekst- en afbeeldingswatermerken toe aan PPT-presentaties in Java met Aspose.Slides for Java.
keywords: watermerk toevoegen aan PPT, tekstwatermerk toevoegen aan PPT, afbeeldingswatermerk toevoegen aan PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Watermerk toevoegen aan een PPT-presentatie met Java" h2="Bouw Java-toepassingen die met server-side API's tekst- of afbeeldingswatermerken in presentatiebestanden invoegen." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Watermerk toevoegen aan een PPT-presentatie via Java" variant="code" %}}

Met [Aspose.Slides for Java](/slides/nl/java/) voegt u tekst- en afbeeldingswatermerken toe aan PPT-presentaties. Voeg een watermerkvorm toe aan een modeldia, zodat het watermerk verschijnt op alle dia's die dat model gebruiken.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekstwatermerk toevoegen aan PPT met Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Afbeeldingswatermerk toevoegen aan een PPT-presentatie met Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een watermerk toevoegen aan PPT met Java" intro="Volg deze stappen om een tekst- of afbeeldingswatermerk toe te voegen aan PPT-bestanden." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het `PPT`-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Selecteer een modeldia met de methode `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `addAutoShape` aan om een watermerkvorm toe te voegen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `addTextFrame` aan om watermerktekst toe te voegen of gebruik `addImage` voor een afbeeldingswatermerk.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de presentatie met watermerk op in PPT-formaat.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Gebouwd met Aspose.Slides" title="Watermerken toevoegen aan PPT-bestanden online" description="De gratis app Aspose.Slides Watermark is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPT-bestanden." button="Aspose.Slides Watermark openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides watermerken toevoegt voordat u code schrijft.
- Voeg een tekst- of afbeeldingswatermerk toe aan uw PPT-bestand.
- Download het bestand met watermerk.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor watermerken" subTitle="Met Java kunt u ook watermerken toevoegen aan de volgende formaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
