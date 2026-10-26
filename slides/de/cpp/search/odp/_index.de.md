---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Text in ODP-Präsentationen mit C++ durchsuchen
url: /de/cpp/search/odp/
description: Durchsuchen Sie Text in ODP-Präsentationen in C++. Finden Sie Text in Präsentationsdateien mit Aspose.Slides for C++.
keywords: Wörter in ODP suchen, Text in ODP finden, Text in ODP-Präsentation suchen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Text in ODP mit C++ durchsuchen" h2="Finden Sie Text in Präsentationsdateien mit Aspose.Slides for C++ – ohne Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Text in einer ODP-Präsentation mit C++ durchsuchen" variant="code" %}}

Mit Aspose.Slides for C++ durchsuchen Sie Text in ODP-Präsentationen. Sammeln Sie mit `SlideUtil::GetAllTextBoxes` die Textrahmen einer Folie und prüfen Sie dann deren Text auf die gesuchte Phrase.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Text in einer ODP-Präsentation mit C++ durchsuchen – Beispiel" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So durchsuchen Sie Text in ODP mit C++" intro="Gehen Sie wie folgt vor, um Text in einer ODP-Präsentation zu durchsuchen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die gewünschte Folie über `Presentation::get_Slides` ab und lesen Sie ihre Textrahmen mit [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) aus.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Prüfen Sie den Text jedes Rahmens auf die gesuchte Phrase.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Entwickelt mit Aspose.Slides" title="Text in ODP-Dateien online durchsuchen" description="Die kostenlose App Aspose.Slides Search basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Search öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Text findet, bevor Sie Code schreiben.
- Durchsuchen Sie Ihre ODP-Datei nach einfachem Text oder regulären Ausdrücken.
- Laden Sie die Treffer als Textdatei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für die Suche" subTitle="Mit C++ können Sie auch Text in den folgenden Formaten durchsuchen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
