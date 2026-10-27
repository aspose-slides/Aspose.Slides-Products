---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Δημιουργία γραφημάτων σε παρουσιάσεις PPTX με Python
url: /el/python-net/chart/pptx/
description: Δημιουργήστε και προσαρμόστε γραφήματα σε παρουσιάσεις PPTX με Python και το Aspose.Slides for Python via .NET.
keywords: δημιουργία γραφήματος, δημιουργία γραφήματος διασποράς, δημιουργία γραφήματος πίτας, δημιουργία γραφήματος δενδρικού χάρτη, δημιουργία γραφήματος μετοχών, δημιουργία θηκογράμματος, δημιουργία ιστογράμματος, δημιουργία γραφήματος χωνιού, γράφημα ηλιακής έκρηξης, γράφημα πολλαπλών κατηγοριών, παρουσίαση PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Δημιουργία γραφημάτων σε παρουσιάσεις PPTX με Python" h2="Δημιουργήστε εφαρμογές Python που δημιουργούν προσαρμόσιμα γραφήματα παρουσιάσεων με τις δικές σας κατηγορίες, σειρές δεδομένων, ετικέτες και μορφοποίηση." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Δημιουργία γραφήματος πίτας σε παρουσίαση PPTX με Python" variant="code" %}}

Το [Aspose.Slides for Python via .NET](/slides/el/python-net/) σάς επιτρέπει να δημιουργήσετε ένα γράφημα πίτας, να αντικαταστήσετε τις προεπιλεγμένες κατηγορίες και σειρές του και να προσαρμόσετε τις ετικέτες και τα χρώματά του. Τα γραφήματα πίτας είναι ιδανικά για να δείξετε πώς λίγες αριθμητικές κατηγορίες συμβάλλουν σε ένα σύνολο. Για περισσότερες επιλογές, δείτε το [Προσαρμογή γραφημάτων πίτας σε παρουσιάσεις](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Δημιουργία γραφήματος πίτας σε παρουσίαση PPTX με Python" >}}
```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]
    chart = slide.shapes.add_chart(slides.charts.ChartType.PIE, 100, 100, 400, 400)

    chart.has_title = True
    chart.chart_title.add_text_frame_for_overriding("Quarterly Sales")
    chart.chart_title.height = 20

    worksheet_index = 0
    workbook = chart.chart_data.chart_data_workbook
    chart.chart_data.series.clear()
    chart.chart_data.categories.clear()

    categories = ("First Quarter", "Second Quarter", "Third Quarter")
    values = (20, 50, 30)

    for row_index, category in enumerate(categories, start=1):
        category_cell = workbook.get_cell(worksheet_index, row_index, 0, category)
        chart.chart_data.categories.add(category_cell)

    series_name_cell = workbook.get_cell(worksheet_index, 0, 1, "Sales")
    series = chart.chart_data.series.add(series_name_cell, chart.type)

    for row_index, value in enumerate(values, start=1):
        value_cell = workbook.get_cell(worksheet_index, row_index, 1, value)
        series.data_points.add_data_point_for_pie_series(value_cell)

    series.labels.default_data_label_format.show_percentage = True
    series.parent_series_group.is_color_varied = True
    series.parent_series_group.first_slice_angle = 180

    fill_colors = (drawing.Color.orange, drawing.Color.blue_violet, drawing.Color.yellow_green)

    for data_point_index, fill_color in enumerate(fill_colors):
        data_point = series.data_points[data_point_index]
        data_point.format.fill.fill_type = slides.FillType.SOLID
        data_point.format.fill.solid_fill_color.color = fill_color

    presentation.save("pie-chart.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να δημιουργήσετε και να προσαρμόσετε ένα γράφημα πίτας σε PPTX με Python" intro="Ακολουθήστε αυτά τα βήματα για να προσθέσετε ένα γράφημα πίτας σε μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε μια παρουσία `Presentation` και αποκτήστε πρόσβαση στην επιθυμητή διαφάνεια μέσω μιας μεταβλητής `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε το `add_chart` με `ChartType.PIE` για να προσθέσετε ένα γράφημα πίτας στη διαφάνεια.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε το `chart_data_workbook` για να αντικαταστήσετε τις προεπιλεγμένες κατηγορίες και σειρές και, στη συνέχεια, ρυθμίστε τις ετικέτες, τα χρώματα και το `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε το `save` με `SaveFormat.PPTX` για να γράψετε την παρουσίαση σε μορφή PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή δημιουργία γραφημάτων PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Chart έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Chart" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides δημιουργεί γραφήματα πριν γράψετε κώδικα.
- Δημιουργήστε ένα γράφημα από δεδομένα Excel ή πίνακα.
- Κατεβάστε το ως αρχείο PPTX ή ως εικόνα.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για γραφήματα" subTitle="Με Python, μπορείτε επίσης να δημιουργήσετε γραφήματα σε άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
