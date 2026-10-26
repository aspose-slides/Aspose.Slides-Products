---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προστασία αρχείων παρουσίασης PPT με Python
url: /el/python-net/protect/ppt/
description: Κρυπτογραφήστε παρουσιάσεις PPT ή ορίστε προστασία εγγραφής με Python.
keywords: προστασία εγγραφής PPT, κρυπτογράφηση PPT με Python, κλείδωμα παρουσίασης PPT, προστασία PPT με Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Προστασία παρουσιάσεων PPT με Python" h2="Δημιουργήστε εφαρμογές Python που κρυπτογραφούν παρουσιάσεις ή ορίζουν προστασία εγγραφής με το Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προστασία παρουσίασης PPT με Python" variant="code" %}}

Το [**Aspose.Slides for Python via .NET**](/slides/el/python-net/) παρέχει δύο διαφορετικούς μηχανισμούς προστασίας. Καλέστε `ProtectionManager.encrypt` για να κρυπτογραφήσετε μια παρουσίαση PPT και να απαιτείται κωδικός για το άνοιγμά της. Εναλλακτικά, καλέστε `ProtectionManager.set_write_protection` για να αποτρέψετε τις τροποποιήσεις χωρίς κρυπτογράφηση του αρχείου. Ο χρήστης μπορεί ακόμη να ανοίξει μια παρουσίαση με προστασία εγγραφής και να αποθηκεύσει τις αλλαγές σε άλλο αρχείο.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κρυπτογράφηση παρουσίασης PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ορισμός προστασίας εγγραφής σε παρουσίαση PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προστατέψετε ένα PPT με Python" intro="Ακολουθήστε αυτά τα βήματα για να προστατέψετε ένα αρχείο PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε το αρχείο PPT με `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε `ProtectionManager.encrypt` για να απαιτείται κωδικός στο άνοιγμα ή `ProtectionManager.set_write_protection` για να αποτρέψετε τις αλλαγές.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την προστατευμένη παρουσίαση ως PPT με `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή προστασία αρχείων PPT με κωδικό πρόσβασης" description="Η δωρεάν εφαρμογή Aspose.Slides Lock έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Lock" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides προστατεύει παρουσιάσεις πριν γράψετε κώδικα.
- Ορίστε κωδικό πρόσβασης για το άνοιγμα ή την επεξεργασία του αρχείου PPT.
- Κατεβάστε το προστατευμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για προστασία" subTitle="Χρησιμοποιήστε Python για να προστατέψετε άλλες υποστηριζόμενες μορφές παρουσίασης." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
