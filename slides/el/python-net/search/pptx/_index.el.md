---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Αναζήτηση κειμένου σε παρουσιάσεις PPTX με Python
url: /el/python-net/search/pptx/
description: Αναζητήστε κείμενο σε παρουσιάσεις PPTX με Python και Aspose.Slides.
keywords: αναζήτηση κειμένου σε PPTX, εύρεση λέξεων σε PPTX, αναζήτηση σε παρουσίαση PPTX με Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Αναζήτηση κειμένου σε παρουσιάσεις PPTX με Python" h2="Δημιουργήστε εφαρμογές Python που βρίσκουν κείμενο σε παρουσιάσεις PowerPoint με το Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αναζήτηση κειμένου σε παρουσίαση PPTX με Python" variant="code" %}}

Με το [Aspose.Slides for Python via .NET](/slides/el/python-net/), μπορείτε να χρησιμοποιήσετε το [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) για να βρείτε σε κάθε διαφάνεια τα πλαίσια κειμένου που περιέχουν μια συγκεκριμένη συμβολοσειρά.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αναζήτηση κειμένου σε παρουσίαση PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αναζητήσετε κείμενο σε PPTX με Python" intro="Ακολουθήστε αυτά τα βήματα για να αναζητήσετε κείμενο σε μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε το αρχείο PPTX με το `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τις διαφάνειες και καλέστε το [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) για καθεμία.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε την ιδιότητα `text` κάθε πλαισίου κειμένου που βρέθηκε.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή αναζήτηση κειμένου σε αρχεία PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Search έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Search" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides βρίσκει κείμενο πριν γράψετε κώδικα.
- Αναζητήστε απλό κείμενο ή κανονικές εκφράσεις στο αρχείο PPTX.
- Κατεβάστε τα αποτελέσματα ως αρχείο κειμένου.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για αναζήτηση" subTitle="Χρησιμοποιήστε Python για να αναζητήσετε κείμενο και σε άλλες υποστηριζόμενες μορφές παρουσιάσεων." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
