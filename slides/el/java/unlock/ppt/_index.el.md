---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ξεκλείδωμα αρχείων παρουσίασης PPT με Java
url: /el/java/unlock/ppt/
description: Καταργήστε κωδικούς πρόσβασης και προστασία εγγραφής από παρουσιάσεις PPT σε Java με το Aspose.Slides for Java.
keywords: Κατάργηση προστασίας εγγραφής PPT, αποκρυπτογράφηση PPT, ξεκλείδωμα παρουσίασης PPT, άρση προστασίας PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ξεκλείδωμα PPT σε Java" h2="Δημιουργήστε εφαρμογές Java που καταργούν κωδικούς πρόσβασης και προστασία εγγραφής από αρχεία παρουσίασης με API από την πλευρά του διακομιστή." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Κατάργηση προστασίας από παρουσίαση PPT σε Java" variant="code" %}}

Με το [Aspose.Slides for Java](/slides/el/java/) μπορείτε να καταργήσετε την κρυπτογράφηση ή την προστασία εγγραφής από μια παρουσίαση PPT. Χρησιμοποιήστε `LoadOptions.setPassword` για να ανοίξετε μια κρυπτογραφημένη παρουσίαση και τις μεθόδους `removeEncryption` και `removeWriteProtection` του `ProtectionManager` για να καταργήσετε τις ρυθμίσεις προστασίας.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κατάργηση προστασίας με κωδικό πρόσβασης από PPT σε Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κατάργηση προστασίας εγγραφής από παρουσίαση PPT σε Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να καταργήσετε τον κωδικό πρόσβασης από ένα PPT σε Java" intro="Ακολουθήστε αυτά τα βήματα για να καταργήσετε την προστασία από μια παρουσίαση PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPT με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε `LoadOptions.setPassword` όταν η παρουσίαση είναι κρυπτογραφημένη.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε `removeEncryption` ή `removeWriteProtection` του αντικειμένου `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την ξεκλείδωτη παρουσίαση με `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακό ξεκλείδωμα αρχείων PPT" description="Η δωρεάν εφαρμογή Aspose.Slides Unlock έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Unlock" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides καταργεί την προστασία πριν γράψετε κώδικα.
- Καταργήστε τον κωδικό πρόσβασης ή την προστασία εγγραφής από το αρχείο PPT.
- Κατεβάστε το ξεκλείδωτο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ξεκλείδωμα" subTitle="Με Java μπορείτε επίσης να καταργήσετε την προστασία από τις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
