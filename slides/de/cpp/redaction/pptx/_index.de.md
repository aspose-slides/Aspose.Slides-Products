---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-Präsentationen mit C++ schwärzen
url: /de/cpp/redaction/pptx/
description: Schwärzen Sie PPTX-Präsentationen in C++. Suchen und ersetzen Sie vertraulichen Text in Präsentationsdateien mit Aspose.Slides for C++.
keywords: PPTX schwärzen, Text in PPTX suchen und ersetzen, PPTX-Präsentation aktualisieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX mit C++ schwärzen" h2="Suchen und ersetzen Sie vertraulichen Text in Präsentationsdateien mit Aspose.Slides for C++ – ohne Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eine PPTX-Präsentation mit C++ schwärzen" variant="code" %}}

Mit Aspose.Slides for C++ schwärzen Sie PPTX-Präsentationen, indem Sie vertraulichen Text auf Folien ersetzen. Durchsuchen Sie die Präsentation mit `SlideUtil::FindAndReplaceText` und einem `Presentation`-Objekt und ersetzen Sie gefundenen Text, bevor Sie die aktualisierte Datei speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eine PPTX-Präsentation mit C++ schwärzen – Beispiel" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So schwärzen Sie PPTX mit C++" intro="Gehen Sie wie folgt vor, um eine PPTX-Präsentation zu schwärzen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPTX-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Suchen und ersetzen Sie vertraulichen Text mit der Methode [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geschwärzte Datei mit `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online schwärzen" description="Die kostenlose App Aspose.Slides Redaction basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Redaction öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Text sucht und ersetzt, bevor Sie Code schreiben.
- Suchen und ersetzen Sie Text in Ihrer PPTX-Datei, auch mit regulären Ausdrücken.
- Laden Sie die geschwärzte Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Schwärzen" subTitle="Mit C++ können Sie auch die folgenden Formate schwärzen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
