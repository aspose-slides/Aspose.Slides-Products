---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: PPT-Anmerkungen mit C++ entfernen
url: /de/cpp/annotation/ppt/ 
description: C++-Quellcode zum Entfernen von Anmerkungen aus PPT-Präsentationen.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Kommentare und Kommentarautoren aus PPT in C++ entfernen" h2="Entwickeln Sie C++-Apps, die mit serverseitigen APIs Kommentare und Autoren in Präsentationsdateien bearbeiten." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Kommentare aus PPT mit C++ entfernen" variant="code" %}}

Entfernen Sie mit [Aspose.Slides for C++](/slides/de/cpp/) Kommentare und Kommentarautoren aus PPT-Präsentationen. Das folgende Beispiel löscht die Kommentare jedes Autors aus `get_CommentAuthors` und leert anschließend die Sammlung der Kommentarautoren.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Anmerkungen aus PPT löschen – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.ppt");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie Kommentare aus PPT mit C++" intro="Gehen Sie wie folgt vor, um Kommentare und Kommentarautoren aus einer PPT-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie Aspose.Slides for C++. Siehe [Installation](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPT-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die Kommentarautoren aus `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Löschen Sie die Kommentare jedes Autors mit `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leeren Sie die Sammlung der Kommentarautoren.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die aktualisierte Präsentation mit `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Entwickelt mit Aspose.Slides" title="PPT-Kommentare online entfernen" description="Die kostenlose App Aspose.Slides Annotation basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPT-Dateien leisten kann." button="Aspose.Slides Annotation öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Kommentare entfernt, bevor Sie Code schreiben.
- Entfernen Sie alle Kommentare aus Ihrer PPT-Datei.
- Laden Sie die bereinigte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Anmerkungen" subTitle="Mit C++ können Sie Anmerkungen auch aus anderen Formaten entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
