---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προβολή ή επεξεργασία μεταδεδομένων ODP με Python
url: /el/python-net/metadata/odp/
description: Προβάλετε και επεξεργαστείτε ενσωματωμένες και προσαρμοσμένες ιδιότητες μεταδεδομένων σε αρχεία ODP με Python.
keywords: επεξεργασία μεταδεδομένων ODP, προβολή μεταδεδομένων ODP, επεξεργασία ιδιοτήτων ODP, προβολή ιδιοτήτων ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Προβολή και επεξεργασία μεταδεδομένων ODP με Python" h2="Δημιουργήστε εφαρμογές Python που διαβάζουν και τροποποιούν ενσωματωμένες και προσαρμοσμένες ιδιότητες παρουσιάσεων με το Aspose.Slides." related="FODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προβολή και τροποποίηση μεταδεδομένων ODP με Python" variant="code" %}}

Το [**Aspose.Slides for Python via .NET**](/slides/el/python-net/) σας επιτρέπει να διαβάζετε και να ενημερώνετε ενσωματωμένα μεταδεδομένα και να προσθέτετε, να ενημερώνετε ή να αφαιρείτε προσαρμοσμένες ιδιότητες εγγράφου σε παρουσιάσεις ODP. Αποκτήστε πρόσβαση σε ένα αντικείμενο [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) μέσω της `Presentation.document_properties`, τροποποιήστε το και αποθηκεύστε την παρουσίαση σε μορφή ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ενημέρωση ενσωματωμένων ιδιοτήτων ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη και αφαίρεση προσαρμοσμένων ιδιοτήτων ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να επεξεργαστείτε μεταδεδομένα ODP με Python" intro="Ακολουθήστε αυτά τα βήματα για να επεξεργαστείτε τα μεταδεδομένα ενός αρχείου ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε το αρχείο ODP με την `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποκτήστε πρόσβαση στο αντικείμενο `IDocumentProperties` μέσω της `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ενημερώστε ενσωματωμένες ιδιότητες ή χρησιμοποιήστε τις `set_custom_property_value` και `remove_custom_property` για προσαρμοσμένες ιδιότητες.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την παρουσίαση με `Presentation.save` και `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προβολή και επεξεργασία μεταδεδομένων ODP online" description="Η δωρεάν εφαρμογή Aspose.Slides Metadata έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Metadata" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει και γράφει ιδιότητες το Aspose.Slides πριν γράψετε κώδικα.
- Προβάλετε και επεξεργαστείτε ενσωματωμένες και προσαρμοσμένες ιδιότητες του αρχείου ODP.
- Αποθηκεύστε και κατεβάστε το ενημερωμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Με Python μπορείτε επίσης να διαχειριστείτε τα μεταδεδομένα άλλων υποστηριζόμενων μορφών παρουσιάσεων." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
