---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: ODP-Anmerkungen mit .NET entfernen
url: /de/net/annotation/odp/ 
description: Entfernen Sie Kommentare und Kommentarautoren aus ODP-Präsentationen in C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Kommentare und Kommentarautoren aus ODP in C# entfernen" h2="Entwickeln Sie .NET-Anwendungen, die mit serverseitigen APIs Kommentare und Autoren in Präsentationsdateien bearbeiten." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Kommentare aus ODP mit C# entfernen" variant="code" %}}

Entfernen Sie mit [Aspose.Slides for .NET](/slides/de/net/) Kommentare und Kommentarautoren aus ODP-Präsentationsdateien. Das folgende Beispiel leert die `Comments`-Sammlung jedes Autors und anschließend die `CommentAuthors`-Sammlung der Präsentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Anmerkungen aus ODP löschen – C#" >}}
```cs
using var presentation = new Presentation("example.odp");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie Kommentare aus ODP mit C#" intro="Gehen Sie wie folgt vor, um Kommentare und Kommentarautoren aus einer ODP-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie Aspose.Slides for .NET. Siehe [Installation](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die Sammlung `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leeren Sie die `Comments`-Sammlung jedes Kommentarautors.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leeren Sie die Sammlung `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die aktualisierte Präsentation mit `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Entwickelt mit Aspose.Slides" title="ODP-Kommentare online entfernen" description="Die kostenlose App Aspose.Slides Annotation basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Annotation öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Kommentare entfernt, bevor Sie Code schreiben.
- Entfernen Sie alle Kommentare aus Ihrer ODP-Datei.
- Laden Sie die bereinigte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Anmerkungen" subTitle="Mit C# können Sie Anmerkungen auch aus anderen Formaten entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
