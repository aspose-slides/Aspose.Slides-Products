---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wasserzeichen zu PPTX-Präsentationsdateien mit Java hinzufügen
url: /de/java/watermark/pptx/
description: Fügen Sie PPTX-Präsentationen in Java mit Aspose.Slides for Java Text- und Bildwasserzeichen hinzu.
keywords: Wasserzeichen zu PPTX hinzufügen, Textwasserzeichen zu PPTX hinzufügen, Bildwasserzeichen zu PPTX hinzufügen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wasserzeichen zu einer PPTX-Präsentation mit Java hinzufügen" h2="Entwickeln Sie Java-Anwendungen, die mit serverseitigen APIs Text- oder Bildwasserzeichen in Präsentationsdateien einfügen." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wasserzeichen zu einer PPTX-Präsentation mit Java hinzufügen – so geht's" variant="code" %}}

Mit [Aspose.Slides for Java](/slides/de/java/) fügen Sie PPTX-Präsentationen Text- und Bildwasserzeichen hinzu. Platzieren Sie eine Wasserzeichenform auf einer Masterfolie, damit das Wasserzeichen auf allen Folien erscheint, die diesen Master verwenden.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Textwasserzeichen zu PPTX mit Java hinzufügen" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bildwasserzeichen zu einer PPTX-Präsentation mit Java hinzufügen" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So fügen Sie PPTX mit Java ein Wasserzeichen hinzu" intro="Gehen Sie wie folgt vor, um PPTX-Dateien ein Text- oder Bildwasserzeichen hinzuzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die `PPTX`-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wählen Sie über die Methode `getMasters` eine Masterfolie aus.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode `addAutoShape` auf, um eine Wasserzeichenform hinzuzufügen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode `addTextFrame` auf, um Wasserzeichentext hinzuzufügen, oder verwenden Sie `addImage` für ein Bildwasserzeichen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die Präsentation mit Wasserzeichen im PPTX-Format.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online mit Wasserzeichen versehen" description="Die kostenlose App Aspose.Slides Watermark basiert auf [Aspose.Slides for Java](https://products.aspose.com/slides/de/java/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Watermark öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Wasserzeichen hinzufügt, bevor Sie Code schreiben.
- Fügen Sie Ihrer PPTX-Datei ein Text- oder Bildwasserzeichen hinzu.
- Laden Sie die Datei mit Wasserzeichen herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Wasserzeichen" subTitle="Mit Java können Sie auch den folgenden Formaten Wasserzeichen hinzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
