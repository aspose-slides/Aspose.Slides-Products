---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 360
title: PPTX-Anmerkungen mit Java entfernen
url: /de/java/annotation/pptx/ 
description: Entfernen Sie Kommentare und Kommentarautoren aus PPTX-Präsentationen in Java mit Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Kommentare und Kommentarautoren aus PPTX in Java entfernen" h2="Entfernen Sie mit Aspose.Slides for Java Kommentare und Kommentarautoren aus Präsentationsdateien." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Kommentare aus PPTX mit Java entfernen" variant="code" %}}

Mit Aspose.Slides for Java entfernen Sie Kommentare und Kommentarautoren aus PPTX-Präsentationen. Laden Sie eine Datei mit der Klasse `Presentation`, durchlaufen Sie die `ICommentAuthor`-Objekte aus `getCommentAuthors`, löschen Sie deren Kommentare und speichern Sie die aktualisierte Präsentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Anmerkungen aus PPTX löschen – Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie Kommentare aus PPTX mit Java" intro="Gehen Sie wie folgt vor, um Kommentare und Kommentarautoren aus einer PPTX-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie Aspose.Slides for Java. Siehe [Installation](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPTX-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die `ICommentAuthor`-Objekte aus `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Löschen Sie die Kommentare jedes Autors mit `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leeren Sie die Sammlung der Kommentarautoren und speichern Sie die aktualisierte PPTX-Datei.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Entwickelt mit Aspose.Slides" title="PPTX-Kommentare online entfernen" description="Die kostenlose App Aspose.Slides Annotation basiert auf [Aspose.Slides for Java](https://products.aspose.com/slides/de/java/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Annotation öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Kommentare entfernt, bevor Sie Code schreiben.
- Entfernen Sie alle Kommentare aus Ihrer PPTX-Datei.
- Laden Sie die bereinigte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Anmerkungen" subTitle="Mit Java können Sie Anmerkungen auch aus anderen Formaten entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
