---
title: Konvertálja a PPT-t Word-be C#-ban
url: /hu/net/conversion/ppt-to-word/
keywords: Konvertálja a PPT-t Word-be, PPT-t Word-be, PPT-t DOC-ba, PowerPoint-ot Word-be, C# API-t, .NET-könyvtárat
description: Konvertálja a PPT-t Word-be C#-ban. Használja a .NET könyvtár API-t a PowerPoint Wordvé konvertálásához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertálja a PPT-t Word-be C#-ban" h2="Hatékony, többplatformos .NET API a PowerPoint Wordvé konvertálásához C# kóddal NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokon" >}}

{{% blocks/products/pf/feature-page-section h2="A PowerPoint konvertálása Word-be az Aspose.Slides és az Aspose.Words használatával" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hu/net/) és [**Aspose.Words for .NET**](https://products.aspose. com/words/net/) hatékony .NET-könyvtárak, amelyek PowerPoint-prezentációk, Word-dokumentumok és egyéb fájlok kezelésére és konvertálására szolgálnak. A PowerPoint Word-be konvertálásakor lényegében a prezentáció diákjainak tartalmát egy Word-dokumentum oldalaira helyezi át.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="A PowerPoint konvertálása Word-be C#-ban" %}}
Néhány sornyi kóddal gyorsan konvertálhatja a PPT-t Word-be

{{% blocks/products/pf/agp/code-block title="C# kód a PowerPoint Word-be konvertálásához" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet a PPT-t Word-be konvertálni" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for .NET** és az **Aspose.Words for .NET** alkalmazást 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adja hozzá a két könyvtárat referenciaként a projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Presentation osztályból és a Doc osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a Word-be konvertálni kívánt PPT-bemutatót.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A diák tartalma alapján képeket és szövegeket generál.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a kapott Word-dokumentumot.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A PowerPointot más formátumú fájlokká is konvertálhatja" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}