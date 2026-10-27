---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: Κατάργηση σχολιασμών από ODP με Java
url: /el/java/annotation/odp/ 
description: Καταργήστε σχόλια και συντάκτες σχολίων από παρουσιάσεις ODP σε Java με το Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Κατάργηση σχολίων και συντακτών σχολίων από ODP σε Java" h2="Χρησιμοποιήστε το Aspose.Slides for Java για να καταργήσετε σχόλια και συντάκτες σχολίων από αρχεία παρουσιάσεων." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Κατάργηση σχολίων από ODP μέσω Java" variant="code" %}}

Το Aspose.Slides for Java σάς επιτρέπει να καταργείτε σχόλια και συντάκτες σχολίων από παρουσιάσεις ODP. Φορτώστε ένα αρχείο με την κλάση `Presentation`, διατρέξτε τα αντικείμενα `ICommentAuthor` από το `getCommentAuthors`, διαγράψτε τα σχόλιά τους και αποθηκεύστε την ενημερωμένη παρουσίαση.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Διαγραφή σχολιασμών από ODP – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να καταργήσετε σχόλια από ODP μέσω Java" intro="Ακολουθήστε αυτά τα βήματα για να καταργήσετε σχόλια και συντάκτες σχολίων από μια παρουσίαση ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το Aspose.Slides for Java. Δείτε [Εγκατάσταση](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τα αντικείμενα `ICommentAuthor` από το `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαγράψτε τα σχόλια κάθε συντάκτη με `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αδειάστε τη συλλογή συντακτών σχολίων και αποθηκεύστε το ενημερωμένο αρχείο ODP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή κατάργηση σχολίων από ODP" description="Η δωρεάν εφαρμογή Aspose.Slides Annotation έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Annotation" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides καταργεί σχόλια πριν γράψετε κώδικα.
- Καταργήστε όλα τα σχόλια από το αρχείο ODP.
- Κατεβάστε το καθαρισμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για σχολιασμούς" subTitle="Με Java, μπορείτε επίσης να καταργήσετε σχολιασμούς από άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
