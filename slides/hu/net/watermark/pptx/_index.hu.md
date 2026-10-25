---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vízjel hozzáadása PPTX bemutatókhoz C#-ban
url: /hu/net/watermark/pptx/
description: Adjon szöveges és képes vízjelet PPTX bemutatókhoz C#-ban az Aspose.Slides for .NET segítségével.
keywords: vízjel hozzáadása PPTX fájlhoz, szöveges vízjel PPTX, képes vízjel PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vízjel hozzáadása PPTX bemutatóhoz C#-ban" h2="Készítsen .NET-alkalmazásokat, amelyek szöveges vagy képes vízjelet szúrnak be bemutatófájlokba." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vízjel hozzáadása PPTX bemutatóhoz C# segítségével" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével szöveges és képes vízjelet adhat PPTX bemutatókhoz. Helyezzen vízjel-alakzatot egy diamintára, hogy a vízjel minden dián megjelenjen, amely ezt a mintát használja.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveges vízjel hozzáadása PPTX fájlhoz C#-ban" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Képes vízjel hozzáadása PPTX bemutatóhoz C#-ban" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Vízjel hozzáadása PPTX fájlhoz C#-ban lépésről lépésre" intro="Kövesse az alábbi lépéseket szöveges vagy képes vízjel hozzáadásához PPTX fájlokhoz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a `PPTX` fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Válasszon diamintát a `Presentation.Masters` gyűjteményből.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg az `AddAutoShape` metódust egy vízjel-alakzat hozzáadásához.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg az `AddTextFrame` metódust a vízjel szövegének hozzáadásához, vagy képes vízjelhez használja az `AddImage` metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a vízjeles fájlt a `SaveFormat.Pptx` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Az Aspose.Slides segítségével készült" title="Vízjel hozzáadása PPTX fájlokhoz online" description="Az ingyenes Aspose.Slides Watermark alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Watermark megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan adja hozzá az Aspose.Slides a vízjeleket, mielőtt kódot írna.
- Adjon szöveges vagy képes vízjelet PPTX fájljához.
- Töltse le a vízjeles fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További vízjelet támogató formátumok" subTitle="C#-ban a következő formátumokhoz is adhat vízjelet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
