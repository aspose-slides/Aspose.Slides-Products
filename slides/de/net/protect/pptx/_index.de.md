---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-Präsentationsdateien mit .NET schützen
url: /de/net/protect/pptx/
description: C#-Quellcode zum Schutz von PPTX-Präsentationen mit einem Kennwort.
keywords: PPTX-Schreibschutz, PPTX verschlüsseln, PPTX-Präsentation sperren, PPTX schützen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-Dateien mit C# sperren oder mit einem Kennwort schützen" h2="Entwickeln Sie .NET-Apps, die Präsentationen mit serverseitigen APIs verschlüsseln und Änderungen einschränken." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine PPTX-Präsentation mit C# schützen" variant="code" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) können Sie eine PPTX-Präsentation verschlüsseln oder ihre Bearbeitung mit einem Kennwort einschränken. Eine mit `ProtectionManager.Encrypt` verschlüsselte Präsentation lässt sich nur mit dem Kennwort öffnen. Mit `ProtectionManager.SetWriteProtection` bleibt die Präsentation lesbar, Änderungen werden jedoch eingeschränkt.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine PPTX-Präsentation mit C# verschlüsseln" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz für eine PPTX-Präsentation mit C# festlegen" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schützen Sie eine PPTX-Präsentation mit C# durch ein Kennwort" intro="Gehen Sie wie folgt vor, um eine PPTX-Präsentation mit einem Kennwort zu schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPTX-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Verschlüsseln Sie die Präsentation mit `ProtectionManager.Encrypt` oder schränken Sie Änderungen mit `ProtectionManager.SetWriteProtection` ein.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geschützte Datei mit `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online mit einem Kennwort schützen" description="Die kostenlose App Aspose.Slides Lock basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Lock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Präsentationen schützt, bevor Sie Code schreiben.
- Legen Sie ein Kennwort zum Öffnen oder Bearbeiten Ihrer PPTX-Datei fest.
- Laden Sie die geschützte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für den Schutz" subTitle="Mit C# können Sie auch die folgenden Formate schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
