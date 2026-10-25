---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προβολή ή επεξεργασία μεταδεδομένων PPTM με C++
url: /el/cpp/metadata/pptm/
description: Προβάλετε και επεξεργαστείτε μεταδεδομένα PPTM σε C++. Ενημερώστε ενσωματωμένες και προσαρμοσμένες ιδιότητες παρουσιάσεων με το Aspose.Slides for C++.
keywords: επεξεργασία μεταδεδομένων PPTM, προβολή μεταδεδομένων PPTM, επεξεργασία ιδιοτήτων PPTM, προβολή ιδιοτήτων PPTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Επεξεργασία μεταδεδομένων PPTM με C++" h2="Χρησιμοποιήστε το Aspose.Slides for C++ για να προβάλετε και να ενημερώσετε ενσωματωμένες και προσαρμοσμένες ιδιότητες σε αρχεία παρουσιάσεων." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Τροποποίηση ιδιοτήτων PPTM με C++" variant="code" %}}

Το Aspose.Slides for C++ σας επιτρέπει να διαβάζετε και να ενημερώνετε μεταδεδομένα σε αρχεία PPTM χωρίς το Microsoft PowerPoint. Χρησιμοποιήστε το αντικείμενο [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) που παρέχει η `Presentation::get_DocumentProperties` για να αλλάξετε ενσωματωμένες ιδιότητες όπως `Author` και `Title` ή να διαχειριστείτε προσαρμοσμένες ιδιότητες με `idx_set`, `GetCustomPropertyName` και `RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Τροποποίηση ενσωματωμένων ιδιοτήτων PPTM – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptm");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.pptm", SaveFormat::Pptm);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη προσαρμοσμένων ιδιοτήτων σε PPTM – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptm");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.pptm", SaveFormat::Pptm);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προβάλετε ή να επεξεργαστείτε μεταδεδομένα PPTM σε C++" intro="Ακολουθήστε αυτά τα βήματα για να προβάλετε ή να επεξεργαστείτε μεταδεδομένα PPTM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPTM με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε το αντικείμενο `DocumentProperties` με τη `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε ή ενημερώστε ενσωματωμένες ιδιότητες όπως `Author` και `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε, διαβάστε ή αφαιρέστε προσαρμοσμένες ιδιότητες με `idx_set`, `GetCustomPropertyName` και `RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προβολή και επεξεργασία μεταδεδομένων PPTM online" description="Η δωρεάν εφαρμογή Aspose.Slides Metadata έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTM." button="Άνοιγμα Aspose.Slides Metadata" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει και γράφει ιδιότητες το Aspose.Slides πριν γράψετε κώδικα.
- Προβάλετε και επεξεργαστείτε ενσωματωμένες και προσαρμοσμένες ιδιότητες του αρχείου PPTM.
- Αποθηκεύστε και κατεβάστε το ενημερωμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Με C++ μπορείτε επίσης να διαχειριστείτε τα μεταδεδομένα των παρακάτω μορφών." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
