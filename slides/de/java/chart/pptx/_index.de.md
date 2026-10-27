---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 160
title: Diagramme zu PPTX-Präsentationen mit Java hinzufügen
url: /de/java/chart/pptx/ 
description: Fügen Sie PPTX-Präsentationen in Java Diagramme hinzu. Erstellen Sie mit Aspose.Slides for Java Diagrammreihen, Kategorien, Datenbeschriftungen und Formatierungen.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-Diagramme in Java erstellen" h2="Erstellen und formatieren Sie mit Aspose.Slides for Java Diagramme in Präsentationsdateien ohne Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Diagramme in PPTX-Dateien mit Java erstellen" %}}

Verwenden Sie [Aspose.Slides for Java](/slides/de/java/), um Diagramme in PPTX-Präsentationen zu erstellen und zu formatieren. Die API bietet Diagrammobjekte wie `IChart`, `IChartDataWorkbook`, `IChartSeries` und `IDataLabel`. Sie können das Paket `aspose-slides` in einem Maven-basierten Projekt installieren, indem Sie das folgende Repository und die folgende Abhängigkeit hinzufügen.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Repository" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Abhängigkeit" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Diagramm in PPTX erstellen – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);

    chart.getChartTitle().addTextFrameForOverriding("Sales by quarter");
    chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
    chart.getChartTitle().setHeight(20);
    chart.setTitle(true);

    chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);

    int defaultWorksheetIndex = 0;
    IChartDataWorkbook chartDataWorkbook = chart.getChartData().getChartDataWorkbook();

    chart.getChartData().getSeries().clear();
    chart.getChartData().getCategories().clear();

    chart.getChartData().getSeries().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
    chart.getChartData().getSeries().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());

    chart.getChartData().getCategories().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 1, 0, "Category 1"));
    chart.getChartData().getCategories().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 2, 0, "Category 2"));
    chart.getChartData().getCategories().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 3, 0, "Category 3"));

    IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
    firstSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 1, 1, 20));
    firstSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 2, 1, 50));
    firstSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 3, 1, 30));
    firstSeries.getFormat().getFill().setFillType(FillType.Solid);
    firstSeries.getFormat().getFill().getSolidFillColor().setColor(java.awt.Color.RED);

    IChartSeries secondSeries = chart.getChartData().getSeries().get_Item(1);
    secondSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 1, 2, 30));
    secondSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 2, 2, 10));
    secondSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 3, 2, 60));
    secondSeries.getFormat().getFill().setFillType(FillType.Solid);
    secondSeries.getFormat().getFill().getSolidFillColor().setColor(java.awt.Color.GREEN);

    IDataLabel firstDataLabel = secondSeries.getDataPoints().get_Item(0).getLabel();
    firstDataLabel.getDataLabelFormat().setShowCategoryName(true);

    IDataLabel secondDataLabel = secondSeries.getDataPoints().get_Item(1).getLabel();
    secondDataLabel.getDataLabelFormat().setShowSeriesName(true);

    IDataLabel thirdDataLabel = secondSeries.getDataPoints().get_Item(2).getLabel();
    thirdDataLabel.getDataLabelFormat().setShowValue(true);
    thirdDataLabel.getDataLabelFormat().setShowSeriesName(true);
    thirdDataLabel.getDataLabelFormat().setSeparator("/");

    presentation.save("chart-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So erstellen Sie Diagramme in PPTX-Dateien in Java" intro="Erstellen Sie Diagramme in PPTX-Dateien mit Aspose.Slides for Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie ein `Presentation`-Objekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die erste `ISlide` der Präsentation ab.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie ein `IChart`-Objekt mit Standarddaten hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Legen Sie den Diagrammtitel und die Optionen für Datenbeschriftungen fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie das `IChartDataWorkbook`-Objekt ab und entfernen Sie die Standardreihen und -kategorien.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie neue Diagrammreihen und Kategorien hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Füllen Sie die Reihendaten und legen Sie die Füllfarben der Reihen fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie benutzerdefinierte Datenbeschriftungen für die Diagrammreihe.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die Präsentation mit dem Diagramm.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemanforderungen" intro="Aspose.Slides for Java unterstützt die wichtigsten Desktop- und Serverplattformen. Stellen Sie sicher, dass Ihr Projekt diese Voraussetzungen erfüllt." %}}

-  Microsoft Windows, Linux, macOS oder ein anderes Betriebssystem mit einer unterstützten Java-Laufzeitumgebung.
-  Laden Sie die neueste Version von Aspose.Slides for Java über [Maven](https://releases.aspose.com/java/repo/) herunter.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Entwickelt mit Aspose.Slides" title="PPTX-Diagramme online erstellen" description="Die kostenlose App Aspose.Slides Chart basiert auf [Aspose.Slides for Java](https://products.aspose.com/slides/de/java/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Chart öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Diagramme erstellt, bevor Sie Code schreiben.
- Erstellen Sie ein Diagramm aus Excel- oder Tabellendaten.
- Laden Sie es als PPTX-Datei oder als Bild herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Eine PPTX-Datei ist eine Microsoft PowerPoint-Präsentationsdatei im Open-XML-Format. Sie speichert Folien, Text, Bilder, Diagramme, Formatierungen, Animationen und weitere Präsentationsinhalte in einem gezippten XML-basierten Paket.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Diagramme" subTitle="Mit Java können Sie auch Diagramme in anderen Formaten erstellen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/java/chart/ppt/" name="PPT" description="PowerPoint 97-2003-Präsentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
