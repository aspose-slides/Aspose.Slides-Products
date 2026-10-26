---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ξεκλείδωμα παρουσιάσεων PPTX με C++
url: /el/cpp/unlock/pptx/
description: Ξεκλειδώστε παρουσιάσεις PPTX σε C++. Χρησιμοποιήστε το Aspose.Slides for C++ για να καταργείτε την κρυπτογράφηση και την προστασία εγγραφής από αρχεία παρουσίασης.
keywords: Κατάργηση προστασίας εγγραφής PPTX, αποκρυπτογράφηση PPTX, ξεκλείδωμα παρουσίασης PPTX, άρση προστασίας PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ξεκλείδωμα PPTX σε C++" h2="Χρησιμοποιήστε το Aspose.Slides for C++ για να καταργείτε την κρυπτογράφηση και την προστασία εγγραφής από αρχεία παρουσίασης χωρίς το Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Κατάργηση προστασίας από παρουσίαση PPTX σε C++" variant="code" %}}

Το Aspose.Slides for C++ σάς επιτρέπει να καταργείτε την κρυπτογράφηση ή την προστασία εγγραφής από παρουσιάσεις PPTX. Χρησιμοποιήστε `LoadOptions` για να ανοίξετε ένα κρυπτογραφημένο αρχείο και, στη συνέχεια, το αντικείμενο `ProtectionManager` της κλάσης `Presentation` για να καλέσετε `RemoveEncryption` ή `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κατάργηση προστασίας με κωδικό πρόσβασης από PPTX σε C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κατάργηση προστασίας εγγραφής από παρουσίαση PPTX σε C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να καταργήσετε τον κωδικό πρόσβασης από ένα PPTX σε C++" intro="Ακολουθήστε αυτά τα βήματα για να καταργήσετε την προστασία από μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPTX με την κλάση `Presentation` και με `LoadOptions` όταν απαιτείται κωδικός.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε το αντικείμενο `ProtectionManager` για να καταργήσετε την προστασία.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε `RemoveEncryption` για κρυπτογραφημένα αρχεία ή `RemoveWriteProtection` για αρχεία με προστασία εγγραφής.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το ξεκλείδωτο αρχείο με `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακό ξεκλείδωμα αρχείων PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Unlock έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Unlock" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides καταργεί την προστασία πριν γράψετε κώδικα.
- Καταργήστε τον κωδικό πρόσβασης ή την προστασία εγγραφής από το αρχείο PPTX.
- Κατεβάστε το ξεκλείδωτο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ξεκλείδωμα" subTitle="Με C++ μπορείτε επίσης να καταργήσετε την προστασία από τις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
