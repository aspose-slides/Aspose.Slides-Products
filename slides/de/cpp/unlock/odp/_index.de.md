---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-Präsentationen mit C++ entsperren
url: /de/cpp/unlock/odp/
description: Entsperren Sie ODP-Präsentationen in C++. Entfernen Sie mit Aspose.Slides for C++ Verschlüsselung und Schreibschutz von Präsentationsdateien.
keywords: Schreibschutz von ODP entfernen, ODP entschlüsseln, ODP-Präsentation entsperren, ODP-Schutz aufheben
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP mit C++ entsperren" h2="Entfernen Sie mit Aspose.Slides for C++ Verschlüsselung und Schreibschutz von Präsentationsdateien – ohne Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Schutz von einer ODP-Präsentation mit C++ entfernen" variant="code" %}}

Mit Aspose.Slides for C++ entfernen Sie die Verschlüsselung oder den Schreibschutz von ODP-Präsentationen. Öffnen Sie eine verschlüsselte Datei mit `LoadOptions` und rufen Sie dann über das Objekt `ProtectionManager` der Klasse `Presentation` `RemoveEncryption` oder `RemoveWriteProtection` auf.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kennwortschutz von ODP mit C++ entfernen" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schreibschutz von einer ODP-Präsentation mit C++ entfernen" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So entfernen Sie mit C++ ein Kennwort von ODP" intro="Gehen Sie wie folgt vor, um den Schutz von einer ODP-Präsentation zu entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit der Klasse `Presentation` und – falls ein Kennwort erforderlich ist – mit `LoadOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Entfernen Sie den Schutz mit dem Objekt `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `RemoveEncryption` für verschlüsselte Dateien oder `RemoveWriteProtection` für schreibgeschützte Dateien auf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die entsperrte Datei mit `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Entwickelt mit Aspose.Slides" title="ODP-Dateien online entsperren" description="Die kostenlose App Aspose.Slides Unlock basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Unlock öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides den Schutz entfernt, bevor Sie Code schreiben.
- Entfernen Sie das Kennwort oder den Schreibschutz aus Ihrer ODP-Datei.
- Laden Sie die entsperrte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Entsperren" subTitle="Mit C++ können Sie den Schutz auch von den folgenden Formaten entfernen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
