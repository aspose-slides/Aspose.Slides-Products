---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-Präsentationsdateien mit .NET entsperren
url: /de/net/unlock/odp/
description: C#-Quellcode zum Entfernen des Kennwortschutzes von ODP-Präsentationen.
keywords: ODP-Schreibschutz entfernen, ODP entschlüsseln, ODP-Präsentation entsperren, ODP-Schutz aufheben
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-Dateien mit C# entsperren" h2="Entwickeln Sie .NET-Apps, die mit serverseitigen APIs Verschlüsselung und Schreibschutz von Präsentationen entfernen." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Schutz von einer ODP-Präsentation mit C# entfernen" variant="code" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) entfernen Sie die Verschlüsselung oder den Schreibschutz von einer ODP-Präsentation. Um die Verschlüsselung zu entfernen, laden Sie die Präsentation mit dem richtigen Kennwort und rufen `ProtectionManager.RemoveEncryption` auf. Um den Schreibschutz zu entfernen, rufen Sie `ProtectionManager.RemoveWriteProtection` auf.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Verschlüsselung von einer ODP-Präsentation mit C# entfernen" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz von einer ODP-Präsentation mit C# entfernen" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie den Schutz von einer ODP-Präsentation mit C#" intro="Gehen Sie wie folgt vor, um den Schutz von einer ODP-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Geben Sie bei einer verschlüsselten Datei vor dem Laden das Kennwort über `LoadOptions.Password` an.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie je nach Schutzart `ProtectionManager.RemoveEncryption` oder `ProtectionManager.RemoveWriteProtection` auf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die entsperrte Präsentation mit `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Entwickelt mit Aspose.Slides" title="ODP-Dateien online entsperren" description="Die kostenlose App Aspose.Slides Unlock basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Unlock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides den Schutz entfernt, bevor Sie Code schreiben.
- Entfernen Sie das Kennwort oder den Schreibschutz aus Ihrer ODP-Datei.
- Laden Sie die entsperrte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Entsperren" subTitle="Mit C# können Sie den Schutz auch von den folgenden Formaten entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
