---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-Präsentationsdateien mit Java schützen
url: /de/java/protect/odp/
description: Schützen Sie ODP-Präsentationen in Java. Verschlüsseln Sie Präsentationsdateien und legen Sie einen Schreibschutz fest – mit Aspose.Slides for Java.
keywords: Schreibschutz für ODP, ODP verschlüsseln, ODP-Präsentation sperren, ODP schützen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP mit Java sperren oder mit einem Kennwort schützen" h2="Entwickeln Sie Java-Anwendungen, die Präsentationsdateien mit serverseitigen APIs schützen." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine ODP-Präsentation mit Java schützen" variant="code" %}}

Mit [Aspose.Slides for Java](/slides/de/java/) schützen Sie eine ODP-Präsentation mit einem Kennwort vor dem Öffnen oder vor Änderungen. Rufen Sie über das Objekt `ProtectionManager` der Klasse `Presentation` Methoden wie `encrypt` und `setWriteProtection` auf.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine ODP-Präsentation mit Java verschlüsseln" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz für eine ODP-Präsentation mit Java festlegen" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schützen Sie ODP mit Java durch ein Kennwort" intro="Gehen Sie wie folgt vor, um eine ODP-Präsentation zu schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode `encrypt` oder die Methode `setWriteProtection` des Objekts `ProtectionManager` auf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geschützte Datei mit `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Entwickelt mit Aspose.Slides" title="ODP-Dateien online mit einem Kennwort schützen" description="Die kostenlose App Aspose.Slides Lock basiert auf [Aspose.Slides for Java](https://products.aspose.com/slides/de/java/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Lock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Präsentationen schützt, bevor Sie Code schreiben.
- Legen Sie ein Kennwort zum Öffnen oder Bearbeiten Ihrer ODP-Datei fest.
- Laden Sie die geschützte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für den Schutz" subTitle="Mit Java können Sie auch die folgenden Formate schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
