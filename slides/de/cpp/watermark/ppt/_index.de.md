---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wasserzeichen zu PPT-Präsentationen mit C++ hinzufügen
url: /de/cpp/watermark/ppt/
description: Fügen Sie PPT-Präsentationen in C++ Text- oder Bildwasserzeichen hinzu. Platzieren Sie mit Aspose.Slides for C++ Wasserzeichen auf Präsentationsfolien.
keywords: Wasserzeichen zu PPT hinzufügen, Textwasserzeichen zu PPT hinzufügen, Bildwasserzeichen zu PPT hinzufügen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wasserzeichen zu einer PPT-Präsentation mit C++ hinzufügen" h2="Fügen Sie Präsentationsdateien mit Aspose.Slides for C++ Text- oder Bildwasserzeichen hinzu – ohne Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wasserzeichen zu einer PPT-Präsentation mit C++ hinzufügen – so geht's" variant="code" %}}

Mit Aspose.Slides for C++ fügen Sie PPT-Präsentationen Text- oder Bildwasserzeichen hinzu. Fügen Sie der Masterfolie mit `AddAutoShape` eine Wasserzeichenform hinzu, ergänzen Sie Text mit `AddTextFrame` oder füllen Sie die Form mit einem Bild, das über `File::ReadAllBytes` und `AddImage` geladen wird.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Textwasserzeichen zu PPT mit C++ hinzufügen" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bildwasserzeichen zu einer PPT-Präsentation mit C++ hinzufügen" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So fügen Sie PPT mit C++ ein Wasserzeichen hinzu" intro="Gehen Sie wie folgt vor, um PPT-Dateien ein Text- oder Bildwasserzeichen hinzuzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPT-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wählen Sie die Masterfolie aus der Sammlung `Presentation::get_Masters` aus.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie mit der Methode `AddAutoShape` eine Wasserzeichenform hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie mit der Methode `AddTextFrame` Wasserzeichentext hinzu oder legen Sie mit `AddImage` eine Bildfüllung fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die Datei mit Wasserzeichen mit `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Entwickelt mit Aspose.Slides" title="PPT-Dateien online mit Wasserzeichen versehen" description="Die kostenlose App Aspose.Slides Watermark basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPT-Dateien leisten kann." button="Aspose.Slides Watermark öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Wasserzeichen hinzufügt, bevor Sie Code schreiben.
- Fügen Sie Ihrer PPT-Datei ein Text- oder Bildwasserzeichen hinzu.
- Laden Sie die Datei mit Wasserzeichen herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Wasserzeichen" subTitle="Mit C++ können Sie auch den folgenden Formaten Wasserzeichen hinzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
