---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: POTX-Metadaten mit .NET anzeigen oder bearbeiten
url: /de/net/metadata/potx/
description: C#-Quellcode zum Anzeigen oder Bearbeiten von POTX-Metadaten.
keywords: POTX-Metadaten bearbeiten, POTX-Metadaten anzeigen, POTX-Eigenschaften bearbeiten, POTX-Eigenschaften anzeigen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="POTX-Eigenschaften mit C# bearbeiten" h2="Entwickeln Sie .NET-Anwendungen, die integrierte und benutzerdefinierte Präsentationseigenschaften mit serverseitigen APIs lesen und ändern." related="FODP,ODP,OTP,POT,POTM,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POTX-Eigenschaften mit C# ändern" variant="code" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) können Entwickler auf integrierte und benutzerdefinierte Präsentationseigenschaften zugreifen und sie ändern. Verwenden Sie die Eigenschaft [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) eines `Presentation`-Objekts, um POTX-Metadaten zu lesen und zu aktualisieren.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Integrierte POTX-Eigenschaften ändern – C#" >}}
```cs
using var presentation = new Presentation("presentation.potx");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.potx", SaveFormat.Potx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Benutzerdefinierte Eigenschaften zu POTX hinzufügen – C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.potx", SaveFormat.Potx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So zeigen Sie POTX-Metadaten in C# an oder bearbeiten sie" intro="Gehen Sie wie folgt vor, um POTX-Metadaten anzuzeigen oder zu bearbeiten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die POTX-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie das `DocumentProperties`-Objekt der Präsentation ab.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lesen oder aktualisieren Sie integrierte Eigenschaften wie `Author`, `Title` und `Subject`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Greifen Sie mit `DocumentProperties` auf benutzerdefinierte Eigenschaften zu und ändern Sie sie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Entwickelt mit Aspose.Slides" title="POTX-Metadaten online anzeigen und bearbeiten" description="Die kostenlose App Aspose.Slides Metadata basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen POTX-Dateien leisten kann." button="Aspose.Slides Metadata öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Eigenschaften liest und schreibt, bevor Sie Code schreiben.
- Zeigen Sie integrierte und benutzerdefinierte Eigenschaften Ihrer POTX-Datei an und bearbeiten Sie sie.
- Speichern Sie die aktualisierte Datei und laden Sie sie herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Metadatenformate" subTitle="Mit C# können Sie auch die Metadaten der folgenden Formate verwalten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
