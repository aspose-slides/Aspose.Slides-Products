---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redigera HTML i C#
url: /sv/net/editor/html/
keywords: Redigera HTML, HTML, C# API, .NET Library
description: Redigera HTML i C#. Använd .NET library API för att redigera HTML-fil
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redigera HTML i C#" h2="Kraftfullt plattformsoberoende .NET API för redigering av HTML med C#-kod på NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redigera HTML i C#" variant="code" %}}

Med [**Aspose.Slides for .NET**](https://products.aspose.com/slides/sv/net/) kan du lägga till en ny textrad i ett HTML-dokument med bara några rader kod.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-kod för redigering av HTML" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redigera HTML med Aspose.Slides" %}}

[**Aspose.Slides för .NET**](https://products.aspose.com/slides/sv/net/) är ett kraftfullt .NET-bibliotek som används för att manipulera och redigera presentationer, HTML-dokument och andra filer. Du kan redigera ett HTML-dokument genom att lägga till en ny textrad till det.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man redigerar HTML i C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera **Aspose.Slides för .NET**. Se [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till biblioteket som referens i ditt projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa en instans av klassen Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda HTML-dokumentet du vill redigera.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en ny textrad.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den ändrade HTML-filen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Redigera andra filer" subTitle="Du kan även redigera filer i andra format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
