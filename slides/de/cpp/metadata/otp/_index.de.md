---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: OTP-Metadaten mit C++ anzeigen oder bearbeiten
url: /de/cpp/metadata/otp/
description: OTP-Metadaten in C++ anzeigen und bearbeiten. Aktualisieren Sie integrierte und benutzerdefinierte Präsentationseigenschaften mit Aspose.Slides for C++.
keywords: OTP-Metadaten bearbeiten, OTP-Metadaten anzeigen, OTP-Eigenschaften bearbeiten, OTP-Eigenschaften anzeigen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="OTP-Metadaten mit C++ bearbeiten" h2="Zeigen Sie mit Aspose.Slides for C++ integrierte und benutzerdefinierte Eigenschaften in Präsentationsdateien an und aktualisieren Sie sie." related="FODP,ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="OTP-Eigenschaften mit C++ ändern" variant="code" %}}

Mit Aspose.Slides for C++ lesen und aktualisieren Sie Metadaten in OTP-Dateien ohne Microsoft PowerPoint. Verwenden Sie das von `Presentation::get_DocumentProperties` bereitgestellte Objekt [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/), um integrierte Eigenschaften wie `Author` und `Title` zu ändern oder benutzerdefinierte Eigenschaften mit `idx_set`, `GetCustomPropertyName` und `RemoveCustomProperty` zu verwalten.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Integrierte OTP-Eigenschaften ändern – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.otp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.otp", SaveFormat::Otp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Benutzerdefinierte Eigenschaften zu OTP hinzufügen – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.otp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.otp", SaveFormat::Otp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So zeigen Sie OTP-Metadaten in C++ an oder bearbeiten sie" intro="Gehen Sie wie folgt vor, um OTP-Metadaten anzuzeigen oder zu bearbeiten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die OTP-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie das `DocumentProperties`-Objekt mit `get_DocumentProperties` ab.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lesen oder aktualisieren Sie integrierte Eigenschaften wie `Author` und `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie benutzerdefinierte Eigenschaften mit `idx_set`, `GetCustomPropertyName` und `RemoveCustomProperty` hinzu, lesen oder entfernen Sie sie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Entwickelt mit Aspose.Slides" title="OTP-Metadaten online anzeigen und bearbeiten" description="Die kostenlose App Aspose.Slides Metadata basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen OTP-Dateien leisten kann." button="Aspose.Slides Metadata öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Eigenschaften liest und schreibt, bevor Sie Code schreiben.
- Zeigen Sie integrierte und benutzerdefinierte Eigenschaften Ihrer OTP-Datei an und bearbeiten Sie sie.
- Speichern Sie die aktualisierte Datei und laden Sie sie herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Metadatenformate" subTitle="Mit C++ können Sie auch die Metadaten der folgenden Formate verwalten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
