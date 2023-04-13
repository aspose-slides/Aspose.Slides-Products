---
title: Konwertuj PPT na Word w C#
url: /pl/net/conversion/ppt-to-word/
keywords: Konwertuj PPT na Word, PPT na Word, PPT na DOC, PowerPoint na Word, C# API, .NET Library
description: Konwertuj PPT na Word w C#. Użyj interfejsu API biblioteki platformy .NET, aby przekonwertować program PowerPoint na program Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj PPT na Word w C#" h2="Potężny, wieloplatformowy interfejs API platformy .NET do konwersji programu PowerPoint na program Word przy użyciu kodu C# w platformach NET Framework, .NET Core, Windows Azure, Mono lub Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PowerPoint na Word za pomocą Aspose.Slides i Aspose.Words" %}}

[**Aspose.Slides dla .NET**](https://products.aspose.com/slides/pl/net/) i [**Aspose.Words dla .NET**](https://products.aspose. com/words/net/) to potężne biblioteki .NET używane do manipulowania i konwertowania prezentacji programu PowerPoint, dokumentów programu Word i innych plików. Podczas konwertowania programu PowerPoint na program Word zasadniczo przenosisz zawartość slajdów prezentacji na strony w dokumencie programu Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konwertuj PowerPoint na Word w C#" %}}
Możesz szybko przekonwertować PPT na Word za pomocą zaledwie kilku linii kodu

{{% blocks/products/pf/agp/code-block title="Kod C# do konwersji programu PowerPoint do programu Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować PPT na Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj **Aspose.Slides dla .NET** i **Aspose.Words dla .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj dwie biblioteki jako odniesienia w swoim projekcie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utwórz instancję klasy Presentation i klasy Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj prezentację PPT, którą chcesz przekonwertować na format Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Generuj obrazy i teksty na podstawie zawartości slajdów.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynikowy dokument programu Word.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Darmowy konwerter online" sectionDescription="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także konwertować PowerPoint do plików w innych formatach" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}