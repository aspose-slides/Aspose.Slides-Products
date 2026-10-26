---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT-Präsentationsdateien mit Java schwärzen
url: /de/java/redaction/ppt/
description: Suchen und ersetzen Sie Text in PPT-Präsentationen in Java mit Aspose.Slides for Java.
keywords: PPT schwärzen, Text in PPT suchen und ersetzen, PPT-Präsentation aktualisieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT mit Java schwärzen" h2="Entwickeln Sie Java-Anwendungen, die mit serverseitigen APIs Text in Präsentationsdateien suchen und ersetzen." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine PPT-Präsentation mit Java schwärzen" variant="code" %}}

Mit [Aspose.Slides for Java](/slides/de/java/) suchen und ersetzen Sie Text in PPT-Präsentationen. Durchsuchen Sie die Präsentation mit der Methode `SlideUtil.findAndReplaceText` und ersetzen Sie gefundenen Text durch einen neuen Wert.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine PPT-Präsentation mit Java schwärzen – Beispiel" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schwärzen Sie PPT mit Java" intro="Gehen Sie wie folgt vor, um eine PPT-Präsentation zu schwärzen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPT-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode `SlideUtil.findAndReplaceText` auf, um Text zu suchen und zu ersetzen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die aktualisierte Präsentation mit `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Entwickelt mit Aspose.Slides" title="PPT-Dateien online schwärzen" description="Die kostenlose App Aspose.Slides Redaction basiert auf [Aspose.Slides for Java](https://products.aspose.com/slides/de/java/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPT-Dateien leisten kann." button="Aspose.Slides Redaction öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Text sucht und ersetzt, bevor Sie Code schreiben.
- Suchen und ersetzen Sie Text in Ihrer PPT-Datei, auch mit regulären Ausdrücken.
- Laden Sie die geschwärzte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Schwärzen" subTitle="Mit Java können Sie auch die folgenden Formate schwärzen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
