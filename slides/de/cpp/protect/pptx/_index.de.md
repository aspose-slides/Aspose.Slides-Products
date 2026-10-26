---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-Präsentationen mit C++ schützen
url: /de/cpp/protect/pptx/
description: Schützen Sie PPTX-Präsentationen in C++. Verschlüsseln Sie Dateien und legen Sie einen Schreibschutz fest – mit Aspose.Slides for C++.
keywords: Schreibschutz für PPTX, PPTX verschlüsseln, PPTX-Präsentation sperren, PPTX schützen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX mit C++ sperren oder mit einem Kennwort schützen" h2="Verschlüsseln Sie Präsentationen und legen Sie einen Schreibschutz fest – mit Aspose.Slides for C++ und ohne Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine PPTX-Präsentation mit C++ schützen" variant="code" %}}

Mit Aspose.Slides for C++ schützen Sie PPTX-Präsentationen vor dem Öffnen oder vor Änderungen. Verwenden Sie das Objekt `ProtectionManager` der Klasse `Presentation`, um eine Datei mit `Encrypt` zu verschlüsseln oder die Bearbeitung mit `SetWriteProtection` einzuschränken.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine PPTX-Präsentation mit C++ verschlüsseln" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz für eine PPTX-Präsentation mit C++ festlegen" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schützen Sie PPTX mit C++ durch ein Kennwort" intro="Gehen Sie wie folgt vor, um eine PPTX-Präsentation zu schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPTX-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Schützen Sie die Präsentation mit dem Objekt `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Verwenden Sie `Encrypt` für den Kennwortschutz oder `SetWriteProtection` für den Schreibschutz.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geschützte Datei mit `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online mit einem Kennwort schützen" description="Die kostenlose App Aspose.Slides Lock basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Lock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Präsentationen schützt, bevor Sie Code schreiben.
- Legen Sie ein Kennwort zum Öffnen oder Bearbeiten Ihrer PPTX-Datei fest.
- Laden Sie die geschützte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für den Schutz" subTitle="Mit C++ können Sie auch die folgenden Formate schützen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
