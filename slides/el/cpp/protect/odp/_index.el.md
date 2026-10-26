---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προστασία παρουσιάσεων ODP με C++
url: /el/cpp/protect/odp/
description: Προστατέψτε παρουσιάσεις ODP σε C++. Χρησιμοποιήστε το Aspose.Slides for C++ για να κρυπτογραφείτε αρχεία και να ορίζετε προστασία εγγραφής.
keywords: Προστασία εγγραφής ODP, κρυπτογράφηση ODP, κλείδωμα παρουσίασης ODP, προστασία ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Κλείδωμα ή προστασία ODP με κωδικό πρόσβασης σε C++" h2="Χρησιμοποιήστε το Aspose.Slides for C++ για να κρυπτογραφείτε παρουσιάσεις και να ορίζετε προστασία εγγραφής χωρίς το Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προστασία παρουσίασης ODP σε C++" variant="code" %}}

Το Aspose.Slides for C++ σάς επιτρέπει να προστατεύετε παρουσιάσεις ODP από άνοιγμα ή τροποποίηση. Χρησιμοποιήστε το αντικείμενο `ProtectionManager` της κλάσης `Presentation` για να κρυπτογραφήσετε ένα αρχείο με `Encrypt` ή να περιορίσετε την επεξεργασία με `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κρυπτογράφηση παρουσίασης ODP σε C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ορισμός προστασίας εγγραφής σε παρουσίαση ODP σε C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προστατέψετε ένα ODP με κωδικό πρόσβασης σε C++" intro="Ακολουθήστε αυτά τα βήματα για να προστατέψετε μια παρουσίαση ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προστατέψτε την παρουσίαση με το αντικείμενο `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε `Encrypt` για προστασία με κωδικό πρόσβασης ή `SetWriteProtection` για προστασία εγγραφής.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το προστατευμένο αρχείο με `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή προστασία αρχείων ODP με κωδικό πρόσβασης" description="Η δωρεάν εφαρμογή Aspose.Slides Lock έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Lock" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides προστατεύει παρουσιάσεις πριν γράψετε κώδικα.
- Ορίστε κωδικό πρόσβασης για το άνοιγμα ή την επεξεργασία του αρχείου ODP.
- Κατεβάστε το προστατευμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για προστασία" subTitle="Με C++ μπορείτε επίσης να προστατέψετε τις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
