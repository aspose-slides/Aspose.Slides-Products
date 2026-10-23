---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Επεξεργασία PDF σε Python
url: /el/python-net/editor/pdf/
keywords: Επεξεργασία PDF, PDF, Python API, Python Library
description: Επεξεργασία PDF σε Python. Χρησιμοποιήστε το API βιβλιοθήκης Python για να επεξεργαστείτε έγγραφο PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Επεξεργασία PDF σε Python" h2="Βιβλιοθήκη Python υψηλής ταχύτητας και πολλαπλών πλατφορμών για επεξεργασία PDF με χρήση κώδικα Python" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργασία PDF σε Python" variant="code" %}}

Χρησιμοποιώντας το [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο PDF με λίγα μόνο γραμμές κώδικα.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας Python για επεξεργασία PDF" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργαστείτε το PDF χρησιμοποιώντας το Aspose.Slides" %}}

Η [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/) είναι μια ισχυρή βιβλιοθήκη Python που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων, εγγράφων PDF και άλλων αρχείων . Μπορείτε να επεξεργαστείτε ένα έγγραφο PDF προσθέτοντας μια νέα γραμμή κειμένου σε αυτό.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να επεξεργαστείτε το PDF στην Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το **Aspose.Slides για Python μέσω .NET**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το έγγραφο PDF που θέλετε να επεξεργαστείτε.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια νέα γραμμή κειμένου.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αλλαγμένο αρχείο PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Δημιουργήθηκε με το Aspose.Slides" title="Επεξεργασία αρχείων PPTX online" description="Η δωρεάν εφαρμογή Aspose.Slides Editor έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Editor" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς χειρίζεται το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε τα αρχεία PPTX και επεξεργαστείτε τα αμέσως.
- Αποθηκεύστε και κατεβάστε το επεξεργασμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Επεξεργαστείτε άλλα αρχεία" subTitle="Μπορείτε επίσης να επεξεργαστείτε αρχεία σε άλλες μορφές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
