---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Watermerk toevoegen aan ODP-presentaties met C#
url: /nl/net/watermark/odp/
description: Voeg tekst- en afbeeldingswatermerken toe aan ODP-presentaties in C# met Aspose.Slides for .NET.
keywords: watermerk toevoegen aan ODP, tekstwatermerk toevoegen aan ODP, afbeeldingswatermerk toevoegen aan ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Watermerk toevoegen aan een ODP-presentatie met C#" h2="Bouw .NET-toepassingen die tekst- of afbeeldingswatermerken in presentatiebestanden invoegen." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Watermerk toevoegen aan een ODP-presentatie via C#" variant="code" %}}

Met [Aspose.Slides for .NET](/slides/nl/net/) voegt u tekst- en afbeeldingswatermerken toe aan ODP-presentaties. Voeg een watermerkvorm toe aan een modeldia, zodat het watermerk verschijnt op alle dia's die dat model gebruiken.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekstwatermerk toevoegen aan ODP met C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Afbeeldingswatermerk toevoegen aan een ODP-presentatie met C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een watermerk toevoegen aan ODP met C#" intro="Volg deze stappen om een tekst- of afbeeldingswatermerk toe te voegen aan ODP-bestanden." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het `ODP`-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Selecteer een modeldia uit de verzameling `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `AddAutoShape` aan om een watermerkvorm toe te voegen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `AddTextFrame` aan om watermerktekst toe te voegen of gebruik `AddImage` voor een afbeeldingswatermerk.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het bestand met watermerk op met `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Gebouwd met Aspose.Slides" title="Watermerken toevoegen aan ODP-bestanden online" description="De gratis app Aspose.Slides Watermark is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Watermark openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides watermerken toevoegt voordat u code schrijft.
- Voeg een tekst- of afbeeldingswatermerk toe aan uw ODP-bestand.
- Download het bestand met watermerk.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor watermerken" subTitle="Met C# kunt u ook watermerken toevoegen aan de volgende formaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
