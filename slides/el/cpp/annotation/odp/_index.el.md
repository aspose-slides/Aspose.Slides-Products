---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Κατάργηση σχολιασμών από ODP με C++
url: /el/cpp/annotation/odp/ 
description: Πηγαίος κώδικας C++ για κατάργηση σχολιασμών από παρουσιάσεις ODP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Κατάργηση σχολίων και συντακτών σχολίων από ODP σε C++" h2="Δημιουργήστε εφαρμογές C++ που διαχειρίζονται σχόλια και συντάκτες σε αρχεία παρουσιάσεων με API διακομιστή." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Κατάργηση σχολίων από ODP μέσω C++" variant="code" %}}

Χρησιμοποιήστε το [Aspose.Slides for C++](/slides/el/cpp/) για να καταργήσετε σχόλια και συντάκτες σχολίων από παρουσιάσεις ODP. Το παρακάτω παράδειγμα διαγράφει τα σχόλια κάθε συντάκτη από το `get_CommentAuthors` και, στη συνέχεια, αδειάζει τη συλλογή συντακτών σχολίων.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Διαγραφή σχολιασμών από ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.odp");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να καταργήσετε σχόλια από ODP μέσω C++" intro="Ακολουθήστε αυτά τα βήματα για να καταργήσετε σχόλια και συντάκτες σχολίων από μια παρουσίαση ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το Aspose.Slides for C++. Δείτε [Εγκατάσταση](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τους συντάκτες σχολίων από το `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαγράψτε τα σχόλια κάθε συντάκτη με `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αδειάστε τη συλλογή συντακτών σχολίων.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την ενημερωμένη παρουσίαση με `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή κατάργηση σχολίων από ODP" description="Η δωρεάν εφαρμογή Aspose.Slides Annotation έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Annotation" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides καταργεί σχόλια πριν γράψετε κώδικα.
- Καταργήστε όλα τα σχόλια από το αρχείο ODP.
- Κατεβάστε το καθαρισμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για σχολιασμούς" subTitle="Με C++, μπορείτε επίσης να καταργήσετε σχολιασμούς από άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
