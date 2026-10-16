---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PPT naar Word in C#
url: /nl/net/conversion/ppt-to-word/
keywords: Converteer PPT naar Word, PPT naar Word, PPT naar DOC, PowerPoint naar Word, C# API, .NET Library
description: Converteer PPT naar Word in C#. Gebruik de .NET-bibliotheek-API om PowerPoint naar Word te converteren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PPT naar Word in C#" h2="Krachtige platformonafhankelijke .NET API voor het converteren van PowerPoint naar Word met behulp van C#-code op NET Framework-, .NET Core-, Windows Azure-, Mono- of Xamarin-platforms" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PowerPoint naar Word in C#" variant="code" %}}

U kunt PPT snel naar Word converteren met slechts een paar regels code

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-code voor het converteren van PowerPoint naar Word" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PowerPoint naar Word met behulp van Aspose.Slides en Aspose.Words" %}}

[**Aspose.Slides voor .NET**](https://products.aspose.com/slides/nl/net/) en [**Aspose.Words voor .NET**](https://products.aspose. com/words/net/) zijn krachtige .NET-bibliotheken die worden gebruikt om PowerPoint-presentaties, Word-documenten en andere bestanden te manipuleren en te converteren. Wanneer u PowerPoint naar Word converteert, verplaatst u in wezen de inhoud van de dia's van een presentatie naar pagina's in een Word-document.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PPT naar Word te converteren" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer **Aspose.Slides voor .NET** en **Aspose.Words voor .NET**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg de twee bibliotheken toe als referenties in uw project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een instantie van de klasse Presentation en de klasse Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad de PPT-presentatie die u naar Word wilt converteren.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Genereer afbeeldingen en teksten op basis van de inhoud van de dia's.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het resulterende Word-document op.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis online converter"
  description="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PowerPoint ook converteren naar bestanden in andere formaten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
