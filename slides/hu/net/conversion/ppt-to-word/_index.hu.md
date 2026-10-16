---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertálja a PPT-t Word-be C#-ban
url: /hu/net/conversion/ppt-to-word/
keywords: Konvertálja a PPT-t Word-be, PPT-t Word-be, PPT-t DOC-ba, PowerPoint-ot Word-be, C# API-t, .NET-könyvtárat
description: Konvertálja a PPT-t Word-be C#-ban. Használja a .NET könyvtár API-t a PowerPoint Wordvé konvertálásához
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertálja a PPT-t Word-be C#-ban" h2="Hatékony, többplatformos .NET API a PowerPoint Wordvé konvertálásához C# kóddal NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokon" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A PowerPoint konvertálása Word-be C#-ban" variant="code" %}}

Néhány sornyi kóddal gyorsan konvertálhatja a PPT-t Word-be

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# kód a PowerPoint Word-be konvertálásához" >}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A PowerPoint konvertálása Word-be az Aspose.Slides és az Aspose.Words használatával" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hu/net/) és [**Aspose.Words for .NET**](https://products.aspose. com/words/net/) hatékony .NET-könyvtárak, amelyek PowerPoint-prezentációk, Word-dokumentumok és egyéb fájlok kezelésére és konvertálására szolgálnak. A PowerPoint Word-be konvertálásakor lényegében a prezentáció diákjainak tartalmát egy Word-dokumentum oldalaira helyezi át.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan lehet a PPT-t Word-be konvertálni" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az **Aspose.Slides for .NET** és az **Aspose.Words for .NET** alkalmazást{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a két könyvtárat referenciaként a projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy példányt a Presentation osztályból és a Doc osztályból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a Word-be konvertálni kívánt PPT-bemutatót.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A diák tartalma alapján képeket és szövegeket generál.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse el a kapott Word-dokumentumot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes online konverter"
  description="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A PowerPointot más formátumú fájlokká is konvertálhatja" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
