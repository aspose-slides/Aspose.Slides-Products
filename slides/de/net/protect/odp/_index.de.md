---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-Präsentationsdateien mit .NET schützen
url: /de/net/protect/odp/
description: C#-Quellcode zum Schutz von ODP-Präsentationen mit einem Kennwort.
keywords: ODP-Schreibschutz, ODP verschlüsseln, ODP-Präsentation sperren, ODP schützen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-Dateien mit C# sperren oder mit einem Kennwort schützen" h2="Entwickeln Sie .NET-Apps, die Präsentationen mit serverseitigen APIs verschlüsseln und Änderungen einschränken." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine ODP-Präsentation mit C# schützen" variant="code" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) können Sie eine ODP-Präsentation verschlüsseln oder ihre Bearbeitung mit einem Kennwort einschränken. Eine mit `ProtectionManager.Encrypt` verschlüsselte Präsentation lässt sich nur mit dem Kennwort öffnen. Mit `ProtectionManager.SetWriteProtection` bleibt die Präsentation lesbar, Änderungen werden jedoch eingeschränkt.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine ODP-Präsentation mit C# verschlüsseln" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz für eine ODP-Präsentation mit C# festlegen" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schützen Sie eine ODP-Präsentation mit C# durch ein Kennwort" intro="Gehen Sie wie folgt vor, um eine ODP-Präsentation mit einem Kennwort zu schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Verschlüsseln Sie die Präsentation mit `ProtectionManager.Encrypt` oder schränken Sie Änderungen mit `ProtectionManager.SetWriteProtection` ein.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geschützte Datei mit `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Entwickelt mit Aspose.Slides" title="ODP-Dateien online mit einem Kennwort schützen" description="Die kostenlose App Aspose.Slides Lock basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Lock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Präsentationen schützt, bevor Sie Code schreiben.
- Legen Sie ein Kennwort zum Öffnen oder Bearbeiten Ihrer ODP-Datei fest.
- Laden Sie die geschützte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für den Schutz" subTitle="Mit C# können Sie auch die folgenden Formate schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
