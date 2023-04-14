---
title: Konvertera PPTX till Word i C#
url: /sv/net/conversion/pptx-to-word/
keywords: Konvertera PPTX till Word, PPTX till Word, PPTX till DOC, PowerPoint till Word, C# API, .NET Library
description: Konvertera PPTX till Word i C#. Använd .NET library API för att konvertera PowerPoint till Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera PPTX till Word i C#" h2="Kraftfullt plattformsoberoende .NET API för att konvertera PowerPoint till Word med C#-kod på NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera PowerPoint till Word med Aspose.Slides och Aspose.Words" %}}

[**Aspose.Slides för .NET**](https://products.aspose.com/slides/sv/net/) och [**Aspose.Words för .NET**](https://products.aspose. com/words/net/) är kraftfulla .NET-bibliotek som används för att manipulera och konvertera PowerPoint-presentationer, Word-dokument och andra filer. När du konverterar PowerPoint till Word flyttar du i huvudsak innehållet i en presentations bilder till sidor i ett Word-dokument.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konvertera PowerPoint till Word i C#" %}}
Du kan konvertera PPTX till Word snabbt med bara några rader kod

{{% blocks/products/pf/agp/code-block title="C#-kod för att konvertera PowerPoint till Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar PPTX till Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för .NET** och **Aspose.Words för .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till de två biblioteken som referenser i ditt projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa en instans av klassen Presentation och Doc-klassen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPTX-presentationen du vill konvertera till Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa bilder och texter baserat på bildernas innehåll.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara det resulterande Word-dokumentet.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis onlinekonverterare" sectionDescription="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PowerPoint till filer i andra format" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}