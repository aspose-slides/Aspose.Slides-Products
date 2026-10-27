---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7490
title: Δημιουργία γραφημάτων PPT με C++
url: /el/cpp/chart/ppt/ 
description: Παράδειγμα κώδικα C++ για δημιουργία γραφημάτων σε παρουσιάσεις PPT σε Windows και Linux.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Δημιουργία γραφημάτων σε παρουσιάσεις PPT με C++" h2="Δημιουργήστε γραφήματα σε παρουσιάσεις PPT με τα API διακομιστή του Aspose.Slides for C++ χωρίς το Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Δημιουργία γραφημάτων PPT με C++" %}}

Χρησιμοποιήστε το [Aspose.Slides for C++](/slides/el/cpp/) για να δημιουργήσετε γραφήματα σε παρουσιάσεις PPT. Εγκαταστήστε το πακέτο από το [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) ή χρησιμοποιήστε την παρακάτω εντολή στην κονσόλα της Διαχείρισης πακέτων.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εντολή" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Δημιουργία γραφήματος σε PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

// Add a chart with default data.
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0, 0, 500, 500);

// Set the index of the chart data sheet.
int defaultWorksheetIndex = 0;

// Get the chart data workbook.
auto chartDataWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();

// Set the chart title.
chart->get_ChartTitle()->AddTextFrameForOverriding(u"Sample Title");
chart->get_ChartTitle()->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chart->get_ChartTitle()->set_Height(20);
chart->set_HasTitle(true);

// Delete the default generated series and categories.
chart->get_ChartData()->get_Series()->Clear();
chart->get_ChartData()->get_Categories()->Clear();

// Add series.
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 1, ObjectExt::Box(String(u"Series 1"))), chart->get_Type());
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 2, ObjectExt::Box(String(u"Series 2"))), chart->get_Type());

// Add categories.
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 0, ObjectExt::Box(String(u"Category 1"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 0, ObjectExt::Box(String(u"Category 2"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 0, ObjectExt::Box(String(u"Category 3"))));

// Take the first chart series.
auto series = chart->get_ChartData()->get_Series()->idx_get(0);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 1, ObjectExt::Box(20)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 1, ObjectExt::Box(50)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 1, ObjectExt::Box(30)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Blue());

// Take the second chart series.
series = chart->get_ChartData()->get_Series()->idx_get(1);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 2, ObjectExt::Box(30)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 2, ObjectExt::Box(10)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 2, ObjectExt::Box(60)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Orange());

// Show the category name for the first label.
auto dataLabel = series->get_DataPoints()->idx_get(0)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowCategoryName(true);

dataLabel = series->get_DataPoints()->idx_get(1)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);

// Show the value for the third label.
dataLabel = series->get_DataPoints()->idx_get(2)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowValue(true);
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);
dataLabel->get_DataLabelFormat()->set_Separator(u"/");

// Save the PPT file.
presentation->Save(u"column_chart.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να δημιουργήσετε γραφήματα σε αρχεία PPT με C++" intro="Δημιουργήστε ένα γράφημα σε μια παρουσίαση PPT με το Aspose.Slides for C++ σε λίγες γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα αντικείμενο `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποκτήστε πρόσβαση στην πρώτη διαφάνεια.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε ένα γράφημα με προεπιλεγμένα δεδομένα.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ορίστε το ευρετήριο του φύλλου δεδομένων του γραφήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε το βιβλίο εργασίας δεδομένων του γραφήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ορίστε τον τίτλο του γραφήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαγράψτε τις σειρές και τις κατηγορίες που δημιουργήθηκαν από προεπιλογή.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε σειρές και κατηγορίες.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Πάρτε την πρώτη σειρά του γραφήματος και συμπληρώστε τα δεδομένα της.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ορίστε το χρώμα γεμίσματος της σειράς.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εμφανίστε το όνομα κατηγορίας, το όνομα σειράς και την τιμή στις ετικέτες δεδομένων της δεύτερης σειράς.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αρχείο PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for C++ υποστηρίζει τις κύριες πλατφόρμες και τα κύρια λειτουργικά συστήματα. Βεβαιωθείτε ότι το περιβάλλον σας πληροί τις παρακάτω προϋποθέσεις." %}}

-  Microsoft Windows, Linux, macOS ή άλλο συμβατό λειτουργικό σύστημα με το υποστηριζόμενο περιβάλλον εκτέλεσης C++.
-  Αναφορά στη βιβλιοθήκη Aspose.Slides for C++ στο έργο σας.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή δημιουργία γραφημάτων PPT" description="Η δωρεάν εφαρμογή Aspose.Slides Chart έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Chart" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides δημιουργεί γραφήματα πριν γράψετε κώδικα.
- Δημιουργήστε ένα γράφημα από δεδομένα Excel ή πίνακα.
- Κατεβάστε το ως αρχείο PPT ή ως εικόνα.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Ένα αρχείο PPT περιέχει μια συλλογή διαφανειών για μια προβολή παρουσίασης. Χρησιμοποιεί τη δυαδική μορφή αρχείου του Microsoft PowerPoint 97-2003. Ένα αρχείο PPT μπορεί να περιέχει κείμενο, κουκκίδες, εικόνες, πολυμέσα και άλλα ενσωματωμένα αντικείμενα OLE. Η Microsoft εισήγαγε τη νεότερη μορφή PPTX στο PowerPoint 2007. Η PPTX βασίζεται στο Office Open XML και διαφέρει από την παλαιότερη δυαδική μορφή. Αρχεία PPT μπορούν να δημιουργήσουν και άλλες εφαρμογές, όπως το OpenOffice Impress και το Apple Keynote.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για γραφήματα" subTitle="Με C++, μπορείτε επίσης να δημιουργήσετε γραφήματα σε άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/chart/pptx/" name="PPTX" description="Μορφή παρουσίασης Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
