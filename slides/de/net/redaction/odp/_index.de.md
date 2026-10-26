---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-Präsentationsdateien mit .NET schwärzen
url: /de/net/redaction/odp/
description: C#-Quellcode zum Suchen und Ersetzen von Text in ODP-Präsentationen.
keywords: ODP schwärzen, Text in ODP suchen und ersetzen, ODP-Präsentation aktualisieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-Dateien mit C# schwärzen" h2="Entwickeln Sie .NET-Apps, die mit serverseitigen APIs Text in Präsentationen suchen und ersetzen." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine ODP-Präsentation mit C# schwärzen" variant="code" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) suchen und ersetzen Sie Text in einer ODP-Präsentation. Steuern Sie die Suche mit `Presentation.ReplaceText` und `TextSearchOptions` und speichern Sie anschließend die geänderte Präsentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine ODP-Präsentation mit C# schwärzen" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schwärzen Sie eine ODP-Präsentation mit C#" intro="Gehen Sie wie folgt vor, um Text in einer ODP-Präsentation zu ersetzen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ersetzen Sie den gewünschten Text mit [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) und `TextSearchOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geänderte Präsentation mit `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Entwickelt mit Aspose.Slides" title="ODP-Dateien online schwärzen" description="Die kostenlose App Aspose.Slides Redaction basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Redaction öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Text sucht und ersetzt, bevor Sie Code schreiben.
- Suchen und ersetzen Sie Text in Ihrer ODP-Datei, auch mit regulären Ausdrücken.
- Laden Sie die geschwärzte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Schwärzen" subTitle="Mit C# können Sie auch die folgenden Formate schwärzen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
