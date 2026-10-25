---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προβολή ή επεξεργασία μεταδεδομένων αρχείων PPT με Java
url: /el/java/metadata/ppt/
description: Προβάλετε και επεξεργαστείτε μεταδεδομένα PPT σε Java. Ενημερώστε ενσωματωμένες και προσαρμοσμένες ιδιότητες παρουσιάσεων με το Aspose.Slides for Java.
keywords: επεξεργασία μεταδεδομένων PPT, προβολή μεταδεδομένων PPT, επεξεργασία ιδιοτήτων PPT, προβολή ιδιοτήτων PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Επεξεργασία ιδιοτήτων PPT με Java" h2="Δημιουργήστε εφαρμογές Java που τροποποιούν ενσωματωμένες και προσαρμοσμένες ιδιότητες αρχείων παρουσιάσεων με API διακομιστή." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Τροποποίηση ιδιοτήτων PPT με Java" variant="code" %}}

Με το [Aspose.Slides for Java](/slides/el/java/) οι προγραμματιστές μπορούν να διαβάζουν και να τροποποιούν ενσωματωμένες και προσαρμοσμένες ιδιότητες παρουσιάσεων. Χρησιμοποιήστε τη μέθοδο `getDocumentProperties` ενός αντικειμένου `Presentation` για πρόσβαση στο αντικείμενο `IDocumentProperties` του αρχείου.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Τροποποίηση ενσωματωμένων ιδιοτήτων PPT – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.ppt");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη προσαρμοσμένων ιδιοτήτων σε PPT – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προβάλετε ή να επεξεργαστείτε μεταδεδομένα PPT σε Java" intro="Ακολουθήστε αυτά τα βήματα για να προβάλετε ή να επεξεργαστείτε μεταδεδομένα PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο `PPT` με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `getDocumentProperties` για να λάβετε το αντικείμενο `IDocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε ή ενημερώστε ενσωματωμένες ιδιότητες όπως `Author`, `Title`, `Subject` και `Comments`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε και τροποποιήστε προσαρμοσμένες ιδιότητες με `set_Item`, `getCustomPropertyName` και `removeCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προβολή και επεξεργασία μεταδεδομένων PPT online" description="Η δωρεάν εφαρμογή Aspose.Slides Metadata έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Metadata" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει και γράφει ιδιότητες το Aspose.Slides πριν γράψετε κώδικα.
- Προβάλετε και επεξεργαστείτε ενσωματωμένες και προσαρμοσμένες ιδιότητες του αρχείου PPT.
- Αποθηκεύστε και κατεβάστε το ενημερωμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Με Java μπορείτε επίσης να διαχειριστείτε τα μεταδεδομένα των παρακάτω μορφών." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
