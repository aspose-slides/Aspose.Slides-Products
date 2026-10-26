---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Text in PPTX-Präsentationsdateien mit .NET durchsuchen
url: /de/net/search/pptx/
description: C#-Quellcode zum Durchsuchen von Text in PPTX-Präsentationen.
keywords: Text in PPTX durchsuchen, Text in PPTX finden, PPTX-Präsentationstext durchsuchen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Text in PPTX-Dateien mit C# durchsuchen" h2="Entwickeln Sie .NET-Apps, die mit serverseitigen APIs Text in Präsentationen finden." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Text in einer PPTX-Präsentation mit C# durchsuchen" variant="code" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) durchsuchen Sie Text in einer PPTX-Präsentation. Rufen Sie mit `SlideUtil.GetAllTextBoxes` die Textrahmen einer Folie ab und prüfen Sie deren `Text`-Werte auf die gesuchte Phrase.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Text in einer PPTX-Präsentation mit C# durchsuchen" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So durchsuchen Sie Text in einer PPTX-Präsentation mit C#" intro="Gehen Sie wie folgt vor, um Text in einer PPTX-Präsentation zu durchsuchen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPTX-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die gewünschte Folie aus `Presentation.Slides` ab und weisen Sie sie einer Variablen zu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie ihre Textrahmen mit [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) ab.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Prüfen Sie den `Text`-Wert jedes Rahmens auf die gesuchte Phrase.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Entwickelt mit Aspose.Slides" title="Text in PPTX-Dateien online durchsuchen" description="Die kostenlose App Aspose.Slides Search basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Search öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Text findet, bevor Sie Code schreiben.
- Durchsuchen Sie Ihre PPTX-Datei nach einfachem Text oder regulären Ausdrücken.
- Laden Sie die Treffer als Textdatei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für die Suche" subTitle="Mit C# können Sie auch Text in den folgenden Formaten durchsuchen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
