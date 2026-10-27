---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Κατάργηση σχολίων από PPTX σε Python
url: /el/python-net/annotation/pptx/ 
description: Καταργήστε σχόλια και συντάκτες σχολίων από παρουσιάσεις PPTX σε Python με το Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Κατάργηση σχολίων και συντακτών σχολίων από PPTX σε Python" h2="Χρησιμοποιήστε το Aspose.Slides for Python via .NET για να καταργήσετε σχόλια παρουσίασης και τους συντάκτες τους." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Κατάργηση σχολίων από PPTX μέσω Python" variant="code" %}}

Το [Aspose.Slides for Python via .NET](/slides/el/python-net/) παρέχει πρόσβαση στα σχόλια και τους συντάκτες σχολίων μιας παρουσίασης PPTX. Φορτώστε το αρχείο με το `Presentation`, αδειάστε τη συλλογή `comments` κάθε συντάκτη, αδειάστε το `comment_authors` και αποθηκεύστε το αποτέλεσμα σε μορφή PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κατάργηση σχολίων από PPTX σε Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να καταργήσετε σχόλια από PPTX μέσω Python" intro="Ακολουθήστε αυτά τα βήματα για να καταργήσετε όλα τα σχόλια και τους συντάκτες σχολίων από μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε το αρχείο PPTX με το `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε το `comment_authors` και αδειάστε τη συλλογή `comments` κάθε συντάκτη.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αδειάστε τη συλλογή `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε το `save` με `SaveFormat.PPTX` για να γράψετε την ενημερωμένη παρουσίαση PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή κατάργηση σχολίων από PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Annotation έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Annotation" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides καταργεί σχόλια πριν γράψετε κώδικα.
- Καταργήστε όλα τα σχόλια από το αρχείο PPTX.
- Κατεβάστε το καθαρισμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για σχολιασμούς" subTitle="Με Python, μπορείτε επίσης να καταργήσετε σχολιασμούς από άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
