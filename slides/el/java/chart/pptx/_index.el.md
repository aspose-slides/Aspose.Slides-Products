---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 160
title: Προσθήκη γραφημάτων σε παρουσιάσεις PPTX με Java
url: /el/java/chart/pptx/ 
description: Προσθέστε γραφήματα σε παρουσιάσεις PPTX σε Java. Χρησιμοποιήστε το Aspose.Slides for Java για να δημιουργήσετε σειρές, κατηγορίες, ετικέτες δεδομένων και μορφοποίηση.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Δημιουργία γραφημάτων PPTX σε Java" h2="Χρησιμοποιήστε το Aspose.Slides for Java για να δημιουργήσετε και να μορφοποιήσετε γραφήματα σε αρχεία παρουσιάσεων χωρίς το Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Δημιουργία γραφημάτων σε αρχεία PPTX με Java" %}}

Χρησιμοποιήστε το [Aspose.Slides for Java](/slides/el/java/) για να δημιουργήσετε και να μορφοποιήσετε γραφήματα σε παρουσιάσεις PPTX. Το API παρέχει αντικείμενα γραφημάτων όπως `IChart`, `IChartDataWorkbook`, `IChartSeries` και `IDataLabel`. Μπορείτε να εγκαταστήσετε το πακέτο `aspose-slides` σε ένα έργο Maven προσθέτοντας το αποθετήριο και την εξάρτηση παρακάτω.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Αποθετήριο" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εξάρτηση" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Δημιουργία γραφήματος σε PPTX – Java" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να δημιουργήσετε γραφήματα σε αρχεία PPTX σε Java" intro="Δημιουργήστε γραφήματα σε αρχεία PPTX με το Aspose.Slides for Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα αντικείμενο `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε το πρώτο `ISlide` από την παρουσίαση.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε ένα αντικείμενο `IChart` με προεπιλεγμένα δεδομένα.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ορίστε τον τίτλο του γραφήματος και τις επιλογές των ετικετών δεδομένων.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε το αντικείμενο `IChartDataWorkbook` και διαγράψτε τις προεπιλεγμένες σειρές και κατηγορίες.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε νέες σειρές και κατηγορίες γραφήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Συμπληρώστε τα δεδομένα των σειρών και ορίστε τα χρώματα γεμίσματός τους.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε προσαρμοσμένες ετικέτες δεδομένων για τη σειρά του γραφήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την παρουσίαση με το γράφημα.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for Java υποστηρίζει τις κύριες πλατφόρμες επιτραπέζιων υπολογιστών και διακομιστών. Βεβαιωθείτε ότι το έργο σας πληροί αυτές τις προϋποθέσεις." %}}

-  Microsoft Windows, Linux, macOS ή άλλο λειτουργικό σύστημα με υποστηριζόμενο Java Runtime Environment.
-  Λάβετε την πιο πρόσφατη έκδοση του Aspose.Slides for Java από το [Maven](https://releases.aspose.com/java/repo/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή δημιουργία γραφημάτων PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Chart έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Chart" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides δημιουργεί γραφήματα πριν γράψετε κώδικα.
- Δημιουργήστε ένα γράφημα από δεδομένα Excel ή πίνακα.
- Κατεβάστε το ως αρχείο PPTX ή ως εικόνα.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Ένα αρχείο PPTX είναι αρχείο παρουσίασης Microsoft PowerPoint σε μορφή Open XML. Αποθηκεύει διαφάνειες, κείμενο, εικόνες, γραφήματα, μορφοποίηση, κινήσεις και άλλο περιεχόμενο παρουσίασης σε ένα συμπιεσμένο πακέτο βασισμένο σε XML.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για γραφήματα" subTitle="Με Java, μπορείτε επίσης να δημιουργήσετε γραφήματα σε άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/chart/ppt/" name="PPT" description="Παρουσίαση PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
