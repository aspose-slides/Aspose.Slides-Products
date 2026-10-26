---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προστασία αρχείων παρουσίασης PPTX με Java
url: /el/java/protect/pptx/
description: Προστατέψτε παρουσιάσεις PPTX σε Java. Χρησιμοποιήστε το Aspose.Slides for Java για να κρυπτογραφείτε αρχεία παρουσίασης και να ορίζετε προστασία εγγραφής.
keywords: Προστασία εγγραφής PPTX, κρυπτογράφηση αρχείου PPTX, κλείδωμα παρουσίασης PPTX, προστασία PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Κλείδωμα ή προστασία PPTX με κωδικό πρόσβασης σε Java" h2="Δημιουργήστε εφαρμογές Java που προστατεύουν αρχεία παρουσίασης με API από την πλευρά του διακομιστή." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προστασία παρουσίασης PPTX σε Java" variant="code" %}}

Με το [Aspose.Slides for Java](/slides/el/java/) μπορείτε να προστατέψετε μια παρουσίαση PPTX από άνοιγμα ή τροποποίηση ορίζοντας κωδικό πρόσβασης. Χρησιμοποιήστε το αντικείμενο `ProtectionManager` της κλάσης `Presentation` για να καλέσετε μεθόδους όπως `encrypt` και `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κρυπτογράφηση παρουσίασης PPTX σε Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ορισμός προστασίας εγγραφής σε παρουσίαση PPTX σε Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προστατέψετε ένα PPTX με κωδικό πρόσβασης σε Java" intro="Ακολουθήστε αυτά τα βήματα για να προστατέψετε μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPTX με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `encrypt` ή τη μέθοδο `setWriteProtection` του αντικειμένου `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το προστατευμένο αρχείο με `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή προστασία αρχείων PPTX με κωδικό πρόσβασης" description="Η δωρεάν εφαρμογή Aspose.Slides Lock έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Lock" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides προστατεύει παρουσιάσεις πριν γράψετε κώδικα.
- Ορίστε κωδικό πρόσβασης για το άνοιγμα ή την επεξεργασία του αρχείου PPTX.
- Κατεβάστε το προστατευμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για προστασία" subTitle="Με Java μπορείτε επίσης να προστατέψετε τις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
