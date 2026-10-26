---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ξεκλείδωμα παρουσιάσεων PPT με Python
url: /el/python-net/unlock/ppt/
description: Καταργήστε την κρυπτογράφηση και την προστασία εγγραφής από παρουσιάσεις PPT με Python.
keywords: ξεκλείδωμα PPT, κατάργηση κωδικού από PPT, κατάργηση κρυπτογράφησης PPT, κατάργηση προστασίας εγγραφής από PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ξεκλείδωμα παρουσιάσεων PPT με Python" h2="Δημιουργήστε εφαρμογές Python που καταργούν κωδικούς ανοίγματος και προστασία εγγραφής από παρουσιάσεις PPT με το Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Κατάργηση κρυπτογράφησης και προστασίας εγγραφής από PPT με Python" variant="code" %}}

Με το [Aspose.Slides for Python via .NET](/slides/el/python-net/) μπορείτε να καταργήσετε την κρυπτογράφηση που απαιτεί κωδικό για το άνοιγμα μιας παρουσίασης PPT ή να απενεργοποιήσετε την προστασία εγγραφής της. Για να ανοίξετε ένα κρυπτογραφημένο αρχείο, δώστε τον τρέχοντα κωδικό μέσω `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κατάργηση κρυπτογράφησης από παρουσίαση PPT – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κατάργηση προστασίας εγγραφής από παρουσίαση PPT – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να καταργήσετε την προστασία από ένα PPT με Python" intro="Ακολουθήστε αυτά τα βήματα για να καταργήσετε την προστασία από μια παρουσίαση PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Για κρυπτογραφημένο αρχείο PPT, ορίστε τον τρέχοντα κωδικό στο `LoadOptions` και, στη συνέχεια, ανοίξτε το αρχείο με `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε `ProtectionManager.remove_encryption` για να καταργήσετε τον κωδικό ανοίγματος ή `ProtectionManager.remove_write_protection` για να απενεργοποιήσετε την προστασία εγγραφής.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την παρουσίαση που προκύπτει με `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακό ξεκλείδωμα αρχείων PPT" description="Η δωρεάν εφαρμογή Aspose.Slides Unlock έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Unlock" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides καταργεί την προστασία πριν γράψετε κώδικα.
- Καταργήστε τον κωδικό πρόσβασης ή την προστασία εγγραφής από το αρχείο PPT.
- Κατεβάστε το ξεκλείδωτο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ξεκλείδωμα" subTitle="Χρησιμοποιήστε Python για να καταργήσετε την προστασία από άλλες υποστηριζόμενες μορφές παρουσίασης." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
