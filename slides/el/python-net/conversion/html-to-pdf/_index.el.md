---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή HTML σε PDF στην Python
url: /el/python-net/conversion/html-to-pdf/
keywords: HTML σε PDF, Convert HTML σε PDF, Python API, Python Library, HTML, PDF
description: Μετατροπή HTML σε PDF στην Python. Χρησιμοποιήστε το API βιβλιοθήκης Python για να μετατρέψετε αρχεία HTML σε PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή HTML σε PDF στην Python" h2="Βιβλιοθήκη Python υψηλής ταχύτητας και πολλαπλών πλατφορμών που βοηθά στην ανάπτυξη εφαρμογών με δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή HTML σε PDF χρησιμοποιώντας Python" variant="code" %}}

Για να μετατρέψετε το HTML σε PDF, θα χρειαστεί να δημιουργήσετε Παρουσίαση από το αρχείο HTML και να το αποθηκεύσετε ως PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας Python για μετατροπή HTML σε PDF" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("file.html", "rt", encoding="utf-8") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή HTML σε PDF στην Python" %}}

Το [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/) είναι μια ισχυρή βιβλιοθήκη Python για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του HTML σε PDF. Χρησιμοποιώντας το **Aspose.Slides για Python μέσω .NET**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία HTML σε PDF με λίγες μόνο γραμμές κώδικα Python.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides for Python εξάγει αρχεία HTML σε μορφές αρχείων PDF γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το HTML σε PDF και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το HTML σε PDF χρησιμοποιώντας το Aspose.Slides for Python API" intro="Αυτά είναι τα βήματα για τη μετατροπή του HTML σε PDF στην Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/el/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο Python σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε τα αρχεία πηγής HTML στην Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αποτέλεσμα ως αρχείο PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Δωρεάν Online Μετατροπέας"
  description="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Μετατροπή HTML σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το HTML και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
