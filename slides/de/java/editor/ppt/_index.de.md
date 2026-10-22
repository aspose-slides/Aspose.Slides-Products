---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bearbeiten Sie PPT in Java
url: /de/java/editor/ppt/
keywords: PPT bearbeiten, PowerPoint bearbeiten, PPT, PowerPoint, Java-API, Java-Bibliothek
description: Bearbeiten Sie PPT in Java. Verwenden Sie die Java-Bibliotheks-API, um PowerPoint-Präsentationen zu bearbeiten
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bearbeiten Sie PPT in Java" h2="Hochgeschwindigkeits- und plattformübergreifende Java-Bibliothek zum Bearbeiten von PPT mit Java-Code" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bearbeiten Sie PPT in Java" variant="code" %}}

Mit [**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) können Sie mit nur wenigen Codezeilen eine neue Textzeile zu einem PPT-Dokument hinzufügen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java-Code zum Bearbeiten von PPT" >}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bearbeiten Sie PPT mit Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) ist eine leistungsstarke Java-Bibliothek zum Manipulieren und Bearbeiten von Präsentationen. Sie können eine PPT-Präsentation bearbeiten, indem Sie ihr eine neue Textzeile hinzufügen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So bearbeiten Sie PPT in Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie **Aspose.Slides für Java**. Siehe [**Installation**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie eine Instanz der Presentation-Klasse.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPT-Präsentation, die Sie bearbeiten möchten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie eine neue Textzeile hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geänderte PowerPoint-Datei.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Bearbeiten Sie andere Dateien" subTitle="Sie können auch Dateien in anderen Formaten bearbeiten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
