---
title: Converteer PPT naar Word in C#
url: /nl/net/conversion/ppt-to-word/
keywords: Converteer PPT naar Word, PPT naar Word, PPT naar DOC, PowerPoint naar Word, C# API, .NET Library
description: Converteer PPT naar Word in C#. Gebruik de .NET-bibliotheek-API om PowerPoint naar Word te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer PPT naar Word in C#" h2="Krachtige platformonafhankelijke .NET API voor het converteren van PowerPoint naar Word met behulp van C#-code op NET Framework-, .NET Core-, Windows Azure-, Mono- of Xamarin-platforms" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer PowerPoint naar Word met behulp van Aspose.Slides en Aspose.Words" %}}

[**Aspose.Slides voor .NET**](https://products.aspose.com/slides/nl/net/) en [**Aspose.Words voor .NET**](https://products.aspose. com/words/net/) zijn krachtige .NET-bibliotheken die worden gebruikt om PowerPoint-presentaties, Word-documenten en andere bestanden te manipuleren en te converteren. Wanneer u PowerPoint naar Word converteert, verplaatst u in wezen de inhoud van de dia's van een presentatie naar pagina's in een Word-document.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Converteer PowerPoint naar Word in C#" %}}
U kunt PPT snel naar Word converteren met slechts een paar regels code

{{% blocks/products/pf/agp/code-block title="C#-code voor het converteren van PowerPoint naar Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Hoe PPT naar Word te converteren" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installeer **Aspose.Slides voor .NET** en **Aspose.Words voor .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg de twee bibliotheken toe als referenties in uw project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van de klasse Presentation en de klasse Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad de PPT-presentatie die u naar Word wilt converteren.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Genereer afbeeldingen en teksten op basis van de inhoud van de dia's.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het resulterende Word-document op.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis online converter" sectionDescription="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt PowerPoint ook converteren naar bestanden in andere formaten" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}