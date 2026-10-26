---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-Präsentationsdateien mit Java entsperren
url: /de/java/unlock/odp/
description: Entfernen Sie Kennwörter und Schreibschutz von ODP-Präsentationen in Java mit Aspose.Slides for Java.
keywords: Schreibschutz von ODP entfernen, ODP entschlüsseln, ODP-Präsentation entsperren, ODP-Schutz aufheben
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP mit Java entsperren" h2="Entwickeln Sie Java-Anwendungen, die mit serverseitigen APIs Kennwörter und Schreibschutz von Präsentationsdateien entfernen." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Schutz von einer ODP-Präsentation mit Java entfernen" variant="code" %}}

Mit [Aspose.Slides for Java](/slides/de/java/) entfernen Sie die Verschlüsselung oder den Schreibschutz von einer ODP-Präsentation. Öffnen Sie eine verschlüsselte Präsentation mit `LoadOptions.setPassword`, und entfernen Sie die Schutzeinstellungen mit den `ProtectionManager`-Methoden `removeEncryption` und `removeWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kennwortschutz von ODP mit Java entfernen" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz von einer ODP-Präsentation mit Java entfernen" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie mit Java ein Kennwort von ODP" intro="Gehen Sie wie folgt vor, um den Schutz von einer ODP-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Verwenden Sie `LoadOptions.setPassword`, wenn die Präsentation verschlüsselt ist.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `removeEncryption` oder `removeWriteProtection` des Objekts `ProtectionManager` auf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die entsperrte Präsentation mit `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Entwickelt mit Aspose.Slides" title="ODP-Dateien online entsperren" description="Die kostenlose App Aspose.Slides Unlock basiert auf [Aspose.Slides for Java](https://products.aspose.com/slides/de/java/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Unlock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides den Schutz entfernt, bevor Sie Code schreiben.
- Entfernen Sie das Kennwort oder den Schreibschutz aus Ihrer ODP-Datei.
- Laden Sie die entsperrte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Entsperren" subTitle="Mit Java können Sie den Schutz auch von den folgenden Formaten entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
