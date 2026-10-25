---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wasserzeichen zu PPTX-Präsentationen mit C# hinzufügen
url: /de/net/watermark/pptx/
description: Fügen Sie PPTX-Präsentationen in C# mit Aspose.Slides for .NET Text- und Bildwasserzeichen hinzu.
keywords: Wasserzeichen zu PPTX hinzufügen, Textwasserzeichen zu PPTX hinzufügen, Bildwasserzeichen zu PPTX hinzufügen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wasserzeichen zu einer PPTX-Präsentation mit C# hinzufügen" h2="Entwickeln Sie .NET-Anwendungen, die Text- oder Bildwasserzeichen in Präsentationsdateien einfügen." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wasserzeichen zu einer PPTX-Präsentation mit C# hinzufügen – so geht's" variant="code" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) fügen Sie PPTX-Präsentationen Text- und Bildwasserzeichen hinzu. Platzieren Sie eine Wasserzeichenform auf einer Masterfolie, damit das Wasserzeichen auf allen Folien erscheint, die diesen Master verwenden.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Textwasserzeichen zu PPTX mit C# hinzufügen" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bildwasserzeichen zu einer PPTX-Präsentation mit C# hinzufügen" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So fügen Sie PPTX mit C# ein Wasserzeichen hinzu" intro="Gehen Sie wie folgt vor, um PPTX-Dateien ein Text- oder Bildwasserzeichen hinzuzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die `PPTX`-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wählen Sie eine Masterfolie aus der Sammlung `Presentation.Masters` aus.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode `AddAutoShape` auf, um eine Wasserzeichenform hinzuzufügen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode `AddTextFrame` auf, um Wasserzeichentext hinzuzufügen, oder verwenden Sie `AddImage` für ein Bildwasserzeichen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die Datei mit Wasserzeichen mit `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online mit Wasserzeichen versehen" description="Die kostenlose App Aspose.Slides Watermark basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Watermark öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Wasserzeichen hinzufügt, bevor Sie Code schreiben.
- Fügen Sie Ihrer PPTX-Datei ein Text- oder Bildwasserzeichen hinzu.
- Laden Sie die Datei mit Wasserzeichen herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Wasserzeichen" subTitle="Mit C# können Sie auch den folgenden Formaten Wasserzeichen hinzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
