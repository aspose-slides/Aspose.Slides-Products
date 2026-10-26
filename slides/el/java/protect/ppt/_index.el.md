---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προστασία αρχείων παρουσίασης PPT με Java
url: /el/java/protect/ppt/
description: Προστατέψτε παρουσιάσεις PPT σε Java. Χρησιμοποιήστε το Aspose.Slides for Java για να κρυπτογραφείτε αρχεία παρουσίασης και να ορίζετε προστασία εγγραφής.
keywords: Προστασία εγγραφής PPT, κρυπτογράφηση αρχείου PPT, κλείδωμα παρουσίασης PPT, προστασία PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Κλείδωμα ή προστασία PPT με κωδικό πρόσβασης σε Java" h2="Δημιουργήστε εφαρμογές Java που προστατεύουν αρχεία παρουσίασης με API από την πλευρά του διακομιστή." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προστασία παρουσίασης PPT σε Java" variant="code" %}}

Με το [Aspose.Slides for Java](/slides/el/java/) μπορείτε να προστατέψετε μια παρουσίαση PPT από άνοιγμα ή τροποποίηση ορίζοντας κωδικό πρόσβασης. Χρησιμοποιήστε το αντικείμενο `ProtectionManager` της κλάσης `Presentation` για να καλέσετε μεθόδους όπως `encrypt` και `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κρυπτογράφηση παρουσίασης PPT σε Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ορισμός προστασίας εγγραφής σε παρουσίαση PPT σε Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προστατέψετε ένα PPT με κωδικό πρόσβασης σε Java" intro="Ακολουθήστε αυτά τα βήματα για να προστατέψετε μια παρουσίαση PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPT με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `encrypt` ή τη μέθοδο `setWriteProtection` του αντικειμένου `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το προστατευμένο αρχείο με `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή προστασία αρχείων PPT με κωδικό πρόσβασης" description="Η δωρεάν εφαρμογή Aspose.Slides Lock έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Lock" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides προστατεύει παρουσιάσεις πριν γράψετε κώδικα.
- Ορίστε κωδικό πρόσβασης για το άνοιγμα ή την επεξεργασία του αρχείου PPT.
- Κατεβάστε το προστατευμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για προστασία" subTitle="Με Java μπορείτε επίσης να προστατέψετε τις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
