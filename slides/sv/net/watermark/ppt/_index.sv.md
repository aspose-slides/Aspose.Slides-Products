---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lägg till vattenstämpel i PPT-presentationer med C#
url: /sv/net/watermark/ppt/
description: Lägg till text- och bildvattenstämplar i PPT-presentationer i C# med Aspose.Slides for .NET.
keywords: lägg till vattenstämpel i PPT, lägg till textvattenstämpel i PPT, lägg till bildvattenstämpel i PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lägg till vattenstämpel i en PPT-presentation med C#" h2="Bygg .NET-program som infogar text- eller bildvattenstämplar i presentationsfiler." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lägg till vattenstämpel i en PPT-presentation via C#" variant="code" %}}

Med [Aspose.Slides for .NET](/slides/sv/net/) kan du lägga till text- och bildvattenstämplar i PPT-presentationer. Lägg till en vattenstämpelform på en bildbakgrund så att vattenstämpeln visas på alla bilder som använder den bakgrunden.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Lägg till textvattenstämpel i PPT med C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lägg till bildvattenstämpel i en PPT-presentation med C#" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så lägger du till en vattenstämpel i PPT med C#" intro="Följ de här stegen för att lägga till en text- eller bildvattenstämpel i PPT-filer." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in `PPT`-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Välj en bildbakgrund i samlingen `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden `AddAutoShape` för att lägga till en vattenstämpelform.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden `AddTextFrame` för att lägga till vattenstämpeltext eller använd `AddImage` för en bildvattenstämpel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara filen med vattenstämpel med `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Byggd med Aspose.Slides" title="Lägg till vattenstämplar i PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Watermark är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Watermark" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides lägger till vattenstämplar innan du skriver kod.
- Lägg till en text- eller bildvattenstämpel i din PPT-fil.
- Ladda ner filen med vattenstämpel.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöder vattenstämplar" subTitle="Med C# kan du även lägga till vattenstämplar i följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
