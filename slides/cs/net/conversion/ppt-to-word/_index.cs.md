---
title: Převést PPT na Word v C#
url: /cs/net/conversion/ppt-to-word/
keywords: Převod PPT do Wordu, PPT do Wordu, PPT do DOC, PowerPoint do Wordu, C# API, .NET Library
description: Převést PPT na Word v C#. K převodu PowerPointu do Wordu použijte rozhraní API knihovny .NET
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převést PPT na Word v C#" h2="Výkonné rozhraní .NET API pro různé platformy pro převod PowerPointu do Wordu pomocí kódu C# na platformách NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PowerPoint do Wordu pomocí Aspose.Slides a Aspose.Words" %}}

[**Aspose.Slides pro .NET**](https://products.aspose.com/slides/cs/net/) a [**Aspose.Words pro .NET**](https://products.aspose. com/words/net/) jsou výkonné knihovny .NET používané k manipulaci a převodu prezentací PowerPoint, dokumentů aplikace Word a dalších souborů. Při převodu PowerPointu do Wordu v podstatě přesouváte obsah snímků prezentace na stránky v dokumentu Wordu.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Převést PowerPoint na Word v C#" %}}
PPT můžete rychle převést na Word pomocí několika řádků kódu

{{% blocks/products/pf/agp/code-block title="C# kód pro převod PowerPointu do Wordu" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Jak převést PPT do Wordu" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides pro .NET** a **Aspose.Words pro .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte dvě knihovny jako reference do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation a třídy Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte prezentaci PPT, kterou chcete převést do aplikace Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvářejte obrázky a texty na základě obsahu snímků.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledný dokument aplikace Word.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Zdarma online konvertor" sectionDescription="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="PowerPoint můžete také převést na soubory v jiných formátech" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}