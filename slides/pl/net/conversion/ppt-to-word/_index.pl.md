---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPT na Word w C#
url: /pl/net/conversion/ppt-to-word/
keywords: Konwertuj PPT na Word, PPT na Word, PPT na DOC, PowerPoint na Word, C# API, .NET Library
description: Konwertuj PPT na Word w C#. Użyj interfejsu API biblioteki platformy .NET, aby przekonwertować program PowerPoint na program Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPT na Word w C#" h2="Potężny, wieloplatformowy interfejs API platformy .NET do konwersji programu PowerPoint na program Word przy użyciu kodu C# w platformach NET Framework, .NET Core, Windows Azure, Mono lub Xamarin" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PowerPoint na Word w C#" variant="code" %}}

Możesz szybko przekonwertować PPT na Word za pomocą zaledwie kilku linii kodu

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod C# do konwersji programu PowerPoint do programu Word" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PowerPoint na Word za pomocą Aspose.Slides i Aspose.Words" %}}

[**Aspose.Slides dla .NET**](https://products.aspose.com/slides/pl/net/) i [**Aspose.Words dla .NET**](https://products.aspose. com/words/net/) to potężne biblioteki .NET używane do manipulowania i konwertowania prezentacji programu PowerPoint, dokumentów programu Word i innych plików. Podczas konwertowania programu PowerPoint na program Word zasadniczo przenosisz zawartość slajdów prezentacji na strony w dokumencie programu Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PPT na Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides dla .NET** i **Aspose.Words dla .NET**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj dwie biblioteki jako odniesienia w swoim projekcie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz instancję klasy Presentation i klasy Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj prezentację PPT, którą chcesz przekonwertować na format Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Generuj obrazy i teksty na podstawie zawartości slajdów.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynikowy dokument programu Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Darmowy konwerter online"
  description="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także konwertować PowerPoint do plików w innych formatach" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
