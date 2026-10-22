---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Επεξεργασία PPT σε Python
url: /el/python-net/editor/ppt/
keywords: Επεξεργασία PPT, Επεξεργασία PowerPoint, PPT, PowerPoint, Python API, Python Library
description: Επεξεργασία PPT σε Python. Χρησιμοποιήστε το API βιβλιοθήκης Python για να επεξεργαστείτε την παρουσίαση του PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Επεξεργασία PPT σε Python" h2="Βιβλιοθήκη Python υψηλής ταχύτητας και πολλαπλών πλατφορμών για επεξεργασία PPT χρησιμοποιώντας κώδικα Python" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργασία PPT σε Python" variant="code" %}}

Χρησιμοποιώντας το [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο PPT με λίγα μόνο γραμμές κώδικα.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας Python για επεξεργασία PPT" >}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργαστείτε το PPT χρησιμοποιώντας το Aspose.Slides" %}}

Η [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/) είναι μια ισχυρή βιβλιοθήκη Python που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων. Μπορείτε να επεξεργαστείτε μια παρουσίαση PPT προσθέτοντας μια νέα γραμμή κειμένου σε αυτήν.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να επεξεργαστείτε το PPT στην Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το **Aspose.Slides για Python μέσω .NET**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε την παρουσίαση PPT που θέλετε να επεξεργαστείτε.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια νέα γραμμή κειμένου.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αλλαγμένο αρχείο PowerPoint.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Επεξεργαστείτε άλλα αρχεία" subTitle="Μπορείτε επίσης να επεξεργαστείτε αρχεία σε άλλες μορφές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
