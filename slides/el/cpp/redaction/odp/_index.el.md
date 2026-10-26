---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Απόκρυψη δεδομένων σε παρουσιάσεις ODP με C++
url: /el/cpp/redaction/odp/
description: Αποκρύψτε δεδομένα σε παρουσιάσεις ODP σε C++. Χρησιμοποιήστε το Aspose.Slides for C++ για να βρείτε και να αντικαταστήσετε ευαίσθητο κείμενο σε αρχεία παρουσιάσεων.
keywords: απόκρυψη δεδομένων σε ODP, εύρεση και αντικατάσταση κειμένου σε ODP, ενημέρωση παρουσίασης ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Απόκρυψη δεδομένων σε ODP με C++" h2="Χρησιμοποιήστε το Aspose.Slides for C++ για να βρείτε και να αντικαταστήσετε ευαίσθητο κείμενο σε αρχεία παρουσιάσεων χωρίς το Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Απόκρυψη δεδομένων σε παρουσίαση ODP μέσω C++" variant="code" %}}

Το Aspose.Slides for C++ σάς επιτρέπει να αποκρύπτετε δεδομένα σε παρουσιάσεις ODP αντικαθιστώντας ευαίσθητο κείμενο στις διαφάνειες. Χρησιμοποιήστε το `SlideUtil::FindAndReplaceText` με ένα αντικείμενο `Presentation` για να αναζητήσετε στην παρουσίαση και να αντικαταστήσετε το κείμενο που ταιριάζει πριν αποθηκεύσετε το ενημερωμένο αρχείο.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Απόκρυψη δεδομένων σε παρουσίαση ODP με C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αποκρύψετε δεδομένα σε ODP μέσω C++" intro="Ακολουθήστε αυτά τα βήματα για να αποκρύψετε δεδομένα σε μια παρουσίαση ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε τη μέθοδο [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) για να βρείτε και να αντικαταστήσετε ευαίσθητο κείμενο.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το επεξεργασμένο αρχείο με `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή απόκρυψη δεδομένων σε αρχεία ODP" description="Η δωρεάν εφαρμογή Aspose.Slides Redaction έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Redaction" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides βρίσκει και αντικαθιστά κείμενο πριν γράψετε κώδικα.
- Βρείτε και αντικαταστήστε κείμενο στο αρχείο ODP, ακόμη και με κανονικές εκφράσεις.
- Κατεβάστε το επεξεργασμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για απόκρυψη δεδομένων" subTitle="Με C++, μπορείτε επίσης να αποκρύψετε δεδομένα στις ακόλουθες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
