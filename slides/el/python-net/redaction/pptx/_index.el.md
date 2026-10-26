---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Απόκρυψη κειμένου σε παρουσιάσεις PPTX με Python
url: /el/python-net/redaction/pptx/
description: Βρείτε και αντικαταστήστε ευαίσθητο κείμενο σε παρουσιάσεις PPTX με Python.
keywords: απόκρυψη δεδομένων σε PPTX, εύρεση και αντικατάσταση κειμένου σε PPTX, ενημέρωση παρουσίασης PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Απόκρυψη κειμένου σε παρουσιάσεις PPTX με Python" h2="Δημιουργήστε εφαρμογές Python που βρίσκουν και αντικαθιστούν ευαίσθητο κείμενο σε παρουσιάσεις με το Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Απόκρυψη κειμένου σε παρουσίαση PPTX με Python" variant="code" %}}

Με το [Aspose.Slides for Python via .NET](/slides/el/python-net/), μπορείτε να αντικαταστήσετε ευαίσθητο κείμενο σε ολόκληρη την παρουσίαση PPTX. Χρησιμοποιήστε το `Presentation.replace_text` με το `TextSearchOptions` για να ελέγξετε την αναζήτηση και, στη συνέχεια, αποθηκεύστε την τροποποιημένη παρουσίαση.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Απόκρυψη κειμένου σε παρουσίαση PPTX – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.pptx") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αποκρύψετε κείμενο σε παρουσίαση PPTX με Python" intro="Ακολουθήστε αυτά τα βήματα για να αντικαταστήσετε ευαίσθητο κείμενο σε μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε το αρχείο PPTX με το `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε το [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) με το `TextSearchOptions` για να αντικαταστήσετε το απαιτούμενο κείμενο.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την τροποποιημένη παρουσίαση με `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή απόκρυψη δεδομένων σε αρχεία PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Redaction έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Redaction" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides βρίσκει και αντικαθιστά κείμενο πριν γράψετε κώδικα.
- Βρείτε και αντικαταστήστε κείμενο στο αρχείο PPTX, ακόμη και με κανονικές εκφράσεις.
- Κατεβάστε το επεξεργασμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για απόκρυψη δεδομένων" subTitle="Χρησιμοποιήστε Python για να αποκρύψετε κείμενο και σε άλλες υποστηριζόμενες μορφές παρουσιάσεων." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
