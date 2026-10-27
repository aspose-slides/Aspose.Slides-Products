---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7100
title: Δημιουργία γραφημάτων PPTX με .NET
url: /el/net/chart/pptx/ 
description: Δημιουργήστε γραφήματα σε παρουσιάσεις PPTX σε C# με το Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Δημιουργία γραφημάτων PPTX σε C#" h2="Δημιουργήστε εφαρμογές .NET που προσθέτουν γραφήματα σε αρχεία παρουσιάσεων με τα API διακομιστή του Aspose.Slides."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Δημιουργία γραφημάτων PPTX με C#" %}}

Χρησιμοποιήστε το [Aspose.Slides for .NET](/slides/el/net/) για να δημιουργήσετε γραφήματα σε παρουσιάσεις PPTX. Εγκαταστήστε το πακέτο από το [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) ή χρησιμοποιήστε την παρακάτω εντολή στην κονσόλα της Διαχείρισης πακέτων.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εντολή" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Δημιουργία γραφήματος σε PPTX – C#" >}}
```cs
using var presentation = new Presentation();

var slide = presentation.Slides[0];
var chart = slide.Shapes.AddChart(ChartType.ScatterWithSmoothLines, 0, 0, 400, 400);
var defaultWorksheetIndex = 0;
var chartDataWorkbook = chart.ChartData.ChartDataWorkbook;

chart.ChartData.Series.Clear();
chart.ChartData.Series.Add(chartDataWorkbook.GetCell(defaultWorksheetIndex, 1, 1, "Series 1"), chart.Type);
chart.ChartData.Series.Add(chartDataWorkbook.GetCell(defaultWorksheetIndex, 1, 3, "Series 2"), chart.Type);

var firstSeries = chart.ChartData.Series[0];
firstSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 1, 1),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 2, 3));
firstSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 1, 2),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 2, 10));
firstSeries.Type = ChartType.ScatterWithStraightLinesAndMarkers;
firstSeries.Marker.Size = 10;
firstSeries.Marker.Symbol = MarkerStyleType.Star;

var secondSeries = chart.ChartData.Series[1];
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 3, 5),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 4, 2));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 3, 3),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 4, 1));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 4, 3, 2),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 4, 4, 2));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 5, 3, 5),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 5, 4, 1));
secondSeries.Marker.Size = 10;
secondSeries.Marker.Symbol = MarkerStyleType.Circle;

presentation.Save("AsposeScatterChart.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να δημιουργήσετε γραφήματα σε αρχεία PPTX με C#" intro="Δημιουργήστε ένα γράφημα σε μια παρουσίαση PPTX με το Aspose.Slides for .NET σε λίγες γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα αντικείμενο `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε τη διαφάνεια προορισμού από το `presentation.Slides`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `AddChart` για να προσθέσετε ένα γράφημα στη διαφάνεια.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε σειρές και σημεία δεδομένων γραφήματος με το `IChartDataWorkbook`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την παρουσίαση ως αρχείο PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for .NET υποστηρίζει τις κύριες πλατφόρμες και τα κύρια λειτουργικά συστήματα. Βεβαιωθείτε ότι το περιβάλλον σας πληροί τις παρακάτω προϋποθέσεις." %}}

- Ένα υποστηριζόμενο λειτουργικό σύστημα με εγκατεστημένο .NET ή Mono.
- Ένα περιβάλλον ανάπτυξης, όπως το Microsoft Visual Studio.
- Αναφορά στο Aspose.Slides for .NET στο έργο σας. Εγκαταστήστε το από το NuGet ή κατεβάστε το με το κουμπί Λήψη παραπάνω.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή δημιουργία γραφημάτων PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Chart έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Chart" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides δημιουργεί γραφήματα πριν γράψετε κώδικα.
- Δημιουργήστε ένα γράφημα από δεδομένα Excel ή πίνακα.
- Κατεβάστε το ως αρχείο PPTX ή ως εικόνα.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Τα αρχεία με την επέκταση PPTX χρησιμοποιούν τη μορφή παρουσίασης Office Open XML. Ένα αρχείο PPTX μπορεί να περιέχει διαφάνειες με κείμενο, γραφήματα, εικόνες, μορφοποίηση, κινήσεις και άλλο περιεχόμενο παρουσίασης.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για γραφήματα" subTitle="Με C#, μπορείτε επίσης να δημιουργήσετε γραφήματα σε άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/chart/ppt/" name="PPT" description="Παρουσίαση PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
