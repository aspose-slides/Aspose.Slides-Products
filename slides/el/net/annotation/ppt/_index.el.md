---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Κατάργηση σχολιασμών από PPT με .NET
url: /el/net/annotation/ppt/ 
description: Καταργήστε σχόλια και συντάκτες σχολίων από παρουσιάσεις PPT σε C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Κατάργηση σχολίων και συντακτών σχολίων από PPT σε C#" h2="Δημιουργήστε εφαρμογές .NET που διαχειρίζονται σχόλια και συντάκτες σε αρχεία παρουσιάσεων με API διακομιστή." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Κατάργηση σχολίων από PPT μέσω C#" variant="code" %}}

Χρησιμοποιήστε το [Aspose.Slides for .NET](/slides/el/net/) για να καταργήσετε σχόλια και συντάκτες σχολίων από αρχεία παρουσιάσεων PPT. Το παρακάτω παράδειγμα αδειάζει τη συλλογή `Comments` κάθε συντάκτη και, στη συνέχεια, τη συλλογή `CommentAuthors` της παρουσίασης.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Διαγραφή σχολιασμών από PPT – C#" >}}
```cs
using var presentation = new Presentation("example.ppt");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να καταργήσετε σχόλια από PPT μέσω C#" intro="Ακολουθήστε αυτά τα βήματα για να καταργήσετε σχόλια και συντάκτες σχολίων από μια παρουσίαση PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το Aspose.Slides for .NET. Δείτε [Εγκατάσταση](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPT με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τη συλλογή `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αδειάστε τη συλλογή `Comments` κάθε συντάκτη σχολίων.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αδειάστε τη συλλογή `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την ενημερωμένη παρουσίαση με `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή κατάργηση σχολίων από PPT" description="Η δωρεάν εφαρμογή Aspose.Slides Annotation έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Annotation" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides καταργεί σχόλια πριν γράψετε κώδικα.
- Καταργήστε όλα τα σχόλια από το αρχείο PPT.
- Κατεβάστε το καθαρισμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για σχολιασμούς" subTitle="Με C#, μπορείτε επίσης να καταργήσετε σχολιασμούς από άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
